# Day01 - Basic Linux Command
#### Author:- Wasim


## Listing Commands
    sudo --> Super user do
---

    ls --> List content of current working directory
---
    ls -l --> List content of current working directory with detailed output
---
    ll --> List content of current working directory with detailed output as well as hidden file
---
    ls -a --> List all including hidden files and director
---
    ls -i --> List the files and directories with index numbers inodes
---

  -  Inodes --> Inodes are data structures in file systems that store information about files, like their size, permissions, and location on disk. Each file has a unique inode that helps the system manage it
---

    ls -d */ --> List only directories.(We can also specify a patter)
---
    ls *.sh --> List all the having .sh extension
---

## Directoy commands

    pwd --> Display current working directory
---
    cat path_of_directory --> Change directoy to the provided path
---
```cd ~``` or just ```cd``` --> Change directory to home directory from anywhere
---
    cd - --> Go to the last working directory
---
    cd .. --> Change directory one step back
---
    cd ../..  ---> change directory two step back
---
    
## Make Directory

    mkdir directoryName --> To create new directory(folder)
    mkdir -p folder/subfolder/subfolder2 --> Create parent and child directory

### Example:

```
mkdir abc                                # make a new folder named 'abc'

mkdir .abc                               # make a hidden directory (add . before a file to make it hidden)

mkdir A B C                              # make multiple directory at same time

mkdir /home/user/Mydirectory             # make a new folder in a specific location

mkdir -p  A/B/C/D                        # make a nested directory
```
    