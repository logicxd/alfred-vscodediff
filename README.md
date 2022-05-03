<img width=128 src='https://user-images.githubusercontent.com/12219300/166205750-cd113163-843b-450f-8bab-cb05c466a0c3.png'>

<a href="https://github.com/logicxd/alfred-vscodediff/releases/latest/">
  <img alt="Downloads" src="https://img.shields.io/github/downloads/logicxd/alfred-vscodediff/total?color=green&label=Downloads"><br/>
</a>

# Alfred VSCodeDiff

![New](https://user-images.githubusercontent.com/12219300/166203149-ac18d56b-2262-4bda-93d9-f3647a616d54.gif)

Show the diff of the last 2 items in clipboard history using VSCode. This relies on [Alfred 4](https://www.alfredapp.com/) workflows to automate the process.

# How To Use

Download the latest `*.alfredworkflow` file from the [release page](https://github.com/logicxd/alfred-vscodediff/releases).

Commands: 
* Use the keyword `VSCodeDiff` to perform the diff.

# How It Works

![Overview](https://user-images.githubusercontent.com/12219300/166205888-6dac92fa-45b1-423e-a002-e07e024dd871.png)

VSCode provides a way to compares files via terminal with the command `code --diff <file1> <file2>`. So we create 2 temporary files inside the folder `/tmp/com.aungmoe.alfred-vscodediff` and pass those 2 files to the VSCode. Files inside the `/tmp` folder are cleared [after 3 days of not accessing](https://superuser.com/questions/187071/in-macos-how-often-is-tmp-deleted). 

# Modifications

If you want to change the folder path where the files are created, you can open the environments of the workflow (it's the `[x]` button on the top-right) and change the value of `folderPath`.

# Contributions

Not sure what else it can be done but you're welcome to contribute to add onto this workflow! Just create a pull request with a detailed description of your changes. 

# License

[MIT License](https://github.com/logicxd/alfred-vscodediff/blob/main/LICENSE)
