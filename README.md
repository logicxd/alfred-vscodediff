<img width="729" alt="Screen Shot 2023-01-02 at 8 40 46 PM" src="https://user-images.githubusercontent.com/12219300/210301082-933ceea1-3cf3-412f-a264-b7b4b47f2bc7.png">

<h1>
  <img width=36 src='https://user-images.githubusercontent.com/12219300/166205750-cd113163-843b-450f-8bab-cb05c466a0c3.png'>
  AlfredVSCodeDiff
  <a href="https://github.com/logicxd/alfred-vscodediff/releases/latest/">
    <img alt="Downloads" src="https://img.shields.io/github/downloads/logicxd/alfred-vscodediff/total?color=green&label=Downloads"></a>
  <a href="https://github.com/logicxd/alfred-vscodediff/blob/main/LICENSE">
    <img alt="License MIT" src="https://img.shields.io/badge/license-MIT-green"></a>
  <a href="http://www.packal.org/workflow/vscodediff">
    <img alt="PACKAL" src="https://img.shields.io/badge/PACKAL--x.svg?style=social&color=purple"></a>
</h1>

![New](https://user-images.githubusercontent.com/12219300/166203149-ac18d56b-2262-4bda-93d9-f3647a616d54.gif)

Show the diff of the last 2 items in clipboard history using VSCode. This relies on [Alfred](https://www.alfredapp.com/) workflows to automate the process.

# How To Use

1. Setup Visual Studio Code for terminal. 
   1. Open Visual Studio Code
   2. CMD + SHIFT + P (Opens Command Palette)
   3. Search and run "Install 'code' command in PATH"
2. Download the latest `VSCodeDiff.alfredworkflow` file from the [release page](https://github.com/logicxd/alfred-vscodediff/releases). Then just double click it to let Alfred install the workflow.
3. Enable Clipboard History in Alfred

Now you have VSCodeDiff enabled! 

# How It Works

![Overview](https://user-images.githubusercontent.com/12219300/166205888-6dac92fa-45b1-423e-a002-e07e024dd871.png)

VSCode provides a way to compares files via terminal with the command `code --diff <file1> <file2>`. So we create 2 temporary files inside Alfred's cache and use those to compare.

# Contributions

Not sure what else it can be done but you're welcome to contribute to add onto this workflow! Just create a pull request with a detailed description of your changes. 
