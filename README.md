# Introduction_to_linux

## Why Unix
Is a stanadrd operating system in most computer systems in scientific research. It can handle large amount of data in different file formats. i.e text files, fasta files

## basic command-line

### 1. pwd command - prints your current working directory (.)
  list each of the folders you would need to navigate through to get from the root of
  the file system to your current directory. 

### 2. cd - changes your directory 


### 3. ls - list the contents of a directory
  used to list the contents of a directory.
  ls command can be given different options i.e
  -l
  -a
  -h
### 4. mkdir command 
  used for making a directory
  has option
  uasge: mkdir -p outer/inner

### The root directory
/home/evans/mudibo
  - home is the parent directory for evans
  to move up to levels from mudibo directory type
  cd ../.. - absolute path
  cd .. - relative path
  . means current working directory
  .. means parent directory one level up from current working directory
   #### changing directory way back home
    1. cd
    2. cd /
    3. cd ~ 

### Man pages
for command lines that have different options e.g 
ls 
less
sort
cd

### Removing/Deleting files and directories
for file use rm <file>
  rm -i gives opportunity to confirm if you are sure you want to delete
for directory rm -r <directory>
any empty directory can be removed by rmdir <directory>
  
### tab completion
tab completion is used to complete a command or a directory or a file

### touch command
for creating new empty file

### mv command
used to move a file or a directory

### wildcards * and ?
* matches against none or more characters in a file (or directory) name
usage: ls list* - this will list all files in the current directory starting with **list...
ls *list - will list all files in the current directory ending with **....list**

? character matches exactly one character. i.e 
ls ?ouse will match files like **house and mouse, but not grouse**

### cp command
for copying files and directories

