# setupMacAnaconda

## [MacOS版Anacondaのインストール](https://www.python.jp/install/anaconda/macos/install.html)
### Download the package 
  - Download the 64-Bit Graphical Installer from https://www.anaconda.com/products/individual/ 
  
### Install anaconda 
  - Execute the downloaded package to begin installing 

### Set the command-line environment 
  - You cannot use the ```conda``` commands and its environments immediately after the installation 
  - Open a terminal and execute the following command
  ```
  /opt/anaconda3/bin/conda init <Shell Name> 
  ```
  - For ```<Shell Name>```, use the name of the shell that you are currently using. 
  - If you are using ```zsh```, the default shell on macOS Monterey, do:
  ```
  /opt/anaconda3/bin/conda init zsh
  ```
  - Close the terminal and reopen a terminal
  - Then, the Conda environment is already available. 

## Install anaconda 
Follow the detailed instructions on the official page
(> [Installing anaconda on macOS](https://docs.anaconda.com/anaconda/install/mac-os/)).

You may choose the graphical installer or the command-line instructions:
- [macOS graphical install](https://docs.anaconda.com/anaconda/install/mac-os/#macos-graphical-install)
- [Using the command-line install](https://docs.anaconda.com/anaconda/install/mac-os/#using-the-command-line-install)
