# Files and Directories

* [ls](#ls) - list directory contents
* [pwd](#pwd) - print name of current/working directory
* [cat](#cat) - concatenate files and print on the standard output
* [cd](#cd) - change directory
* [mkdir](#mkdir) - make directories
* [rmdir](#rmdir) - remove empty directories
* [rm](#rm) - remove files or directories
* [cp](#cp) - copy files and directories
* [mv](#mv) - move (rename) files
* [touch](#touch) - change file timestamps
* [head](#head) - output the first part of files
* [tail](#tail) - output the last part of files
* [chmod](#chmod) - change file mode bits

## ls

#### Description
List information about the files.

#### Options
* `-l` list contents with extra detail
* `-a` do not ignore entries starting with .

#### Examples
* `ls` - list content from current directory
* `ls /home` - list content from /home directory
* `ls -la`
* `ls file1.txt file2.txt`
* `ls *.txt`

## pwd

#### Description
Print the full filename of current working directory.

#### Options

#### Examples

## cat

#### Description
Concatenate file(s) to standard output.
With no file, or the file is -, read standard input.

#### Options
* `*` - replaces any caracter of the file name

#### Examples
* `cat filename.txt`
* `cat *.txt` - read all files ending with .txt
* `cat file.txt | grep foobar` - read file.txt and redirect to grep to filter and print lines containing foobar

## cd

#### Description
Change the directory

#### Options

#### Examples
* `cd ..` - returns to the parent folder
* `cd foldername` - access the folder

## mkdir

#### Description
Create the directory(ies), if they do not already exist.

#### Options

#### Examples
* `mkdir workspace`

## rmdir

#### Description
Remove the directory(ies), it they are empty.

#### Options

#### Examples
* `rmdir workspace`

## rm

#### Description
Removes each specifies file. By default it does not remove directories.

#### Options
* `-r` - remove directories and their contents recursively
* `-f` - ignore nonexistent files and arguments

#### Examples
* `rm file.txt`
* `rm -r workspace`

## cp

#### Description
Copy source to dest, or multiple sources to directory.

#### Options
* `-r` - copy directories recursively

#### Examples
* `cp file.txt dest.txt`
* `cp file.txt folder/`
* `cp -r sourceFolder/ destFolder/`

## mv

#### Description
Rename source to dest, or rename sources to directory.

#### Options

#### Examples
* `mv old.txt new.txt`
* `mv file.txt folder/`

## touch

#### Description
Update the access and modification times of each file to the current time.

#### Options

#### Examples
* `touch sample.txt`

## head

#### Description
Print the first 10 lines of each file to standard output.

#### Options
* `-n` - print the first n lines

#### Examples
* `head sample.txt` - print the first 10 lines
* `head -n 3 sample.txt` - print the first 3 lines

## tail

#### Description
Print the last 10 lines of each file to standard output.

#### Options
* `-n` - print the last n lines

#### Examples
* `tail sample.txt` - print the last 10 lines
* `tail -n 3 sample.txt` - print the last 3 lines


## chmod

#### Description
Changes the file mode bits of each given file according to mode.

#### Options

#### Examples
* `chmod +x sample.txt` - give execution permission to sample.txt
* `chmod -x sample.txt` - remove execution permission to sample.txt
* `chmod +rwx sample.txt` - give read, write and execution permission to sample.txt
