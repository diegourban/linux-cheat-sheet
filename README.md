# linux-cli

h4. echo

echo Bem vindo
echo "Bem vindo"
echo "Bem vindo" > bemvindo.txt

h4. cat

cat bemvindo.txt

* clear

h4. ls
List directory contents

h5. Options
* `-l` list contents with extra detail
* `-a` list hidden files also

h5. Examples
* `ls -la`

files and directories starting with .(dot) are hidden
Example:
diego@diego-Inspiron-5423:~$ ls -l
drwxrwxr-x 4 diego diego 4096 Dez 15 17:15 apps
-rw-r--r-- 1 diego diego 8980 Dez 12 23:21 examples.desktop
drwxrwxr-x 5 diego diego 4096 Dez 15 20:43 git
When the informations starts with d, it means it is a directory

* man
manual

man pwd
man ls

press q to exit the manual

* pwd
Show the current directory

* whoami
Show the current user
