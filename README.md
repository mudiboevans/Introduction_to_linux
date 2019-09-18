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
cp -r for copying a directory

### clear command
 clears the terminal with of the previous commands.
 
 ### cat (concatenate) command
 displays the contents of a file on the screen
 also used to combine files
 
 ### less command
 writes the contents of a file onto the screen a page at a time.
 press the space-bar for next page
 type q to quit
 less command can also be used for searching a given content in the file
 type less <file name>
  /<specific word in the content you are searchiong for>
  
  ### grep command
  searches files for specified words or patterns.
  it is case sensitive.
  to ignore case distinctions, -i option is used i.e.
  grep -i science Science science.txt
  to search for a phrase or pattern, single quotes are used
  grep -i 'biology of human diseases' science.txt
  other grep options
  -v displays those lines that dont match
  -n precede each matching line with the line number
  -c print only the toal count of matched lines
  
  ### wc command
  used for word count
  wc -w counts words
  wc -l counts lines
  wc -m counts characters
  
  ### mv command can also be used in renaming files
  mv file1 file2 - renames file1 to be file2
  
### nano command
for editing a file

### echo 
displays information of environment variables 
they contain user-specific or system-wide values
that either reflect simple pieces of information (your username), 
or lists of useful locations on the file system
