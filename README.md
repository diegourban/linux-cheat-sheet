# Linux Commands Cheat Sheet

* [Files and Directories](/Files_and_Directories.md)

## echo

#### Name
echo - display a line of text.

#### Description
Echo the String(s) to standard output.

#### Example
* `echo Bem vindo`
* `echo "Bem vindo"`
* `echo "Bem vindo" > filename.txt` redirects the output to the file

## cat

#### Name
cat - concatenate files and print on the standard output.

#### Description
Concatenate file(s) to standard output.
With no file, or the file is -, read standard input.

#### Example
* `cat filename.txt`

## clear

#### Name
clear- clear the terminal screen.

#### Description
Clears your screen if it is possible.

## man

##### Name
man - an interface to the on-line reference manuals.

#### Description
man is the system's manual paper.

#### Example
* `man pwd`
* `man ls`

## whoami

#### Name
whoami - print effective userid.

#### Description
Print the user name associated with the current effective user ID.

----
todo 

files and directories starting with .(dot) are hidden
Example:
diego@diego-Inspiron-5423:~$ ls -l
drwxrwxr-x 4 diego diego 4096 Dez 15 17:15 apps
-rw-r--r-- 1 diego diego 8980 Dez 12 23:21 examples.desktop
drwxrwxr-x 5 diego diego 4096 Dez 15 20:43 git
When the informations starts with d, it means it is a directory
