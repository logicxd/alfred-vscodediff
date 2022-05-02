# Alfred VSCodeDiff

![New](https://user-images.githubusercontent.com/12219300/166203149-ac18d56b-2262-4bda-93d9-f3647a616d54.gif)

Show the diff of the last 2 items in clipboard history using VSCode.

# Old Way

![Old](https://user-images.githubusercontent.com/12219300/166203117-e414b73d-df17-4f9b-9dc3-870f41993b23.gif)

We would have to create 2 new files temporarily, copy-and-paste them, and then select the files to compare.

# How It Works

![Overview](https://user-images.githubusercontent.com/12219300/166204290-33e68e5e-e8ee-4bc1-a53b-2ac8dde35275.png)

VSCode provides a way to compares files via terminal with the command `code --diff <file1> <file2>`. So we create 2 temporary files inside the folder `/tmp/com.aungmoe.alfred-vscodediff` and pass those 2 files to the VSCode.

# Modifications

If you want to change the folder path where the files are created, you can open the environments of the workflow (it's the `[x]` button on the top-right) and change the value of `folderPath`.

# License

[MIT License](https://github.com/logicxd/alfred-vscodediff/blob/main/LICENSE)
