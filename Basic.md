# Basic

* [echo](#echo) - display a line of text
* [clear](#clear) - clear the terminal screen
* [man](#man) - an interface to the on-line reference manuals
* [passwd](#passwd) - change user password
* [su](#su) - change user id or become super user
* [sudo](#sudo) - execute a command as another user

## echo

#### Description
Echo the string(s) to the standard output.

#### Options

#### Examples
* `echo Bem vindo`
* `echo "Bem vindo"`
* `echo "Bem vindo" > filename.txt` redirects the output to the file, and overwrites it
* `echo "Bem vindo" >> filename.txt` redirects the output to the file, and append the text to it

## clear

#### Description
Clears your screen if it is possible.

#### Options

#### Examples
* `clear`

## man

#### Description
Man is the system's manual paper.

#### Options

#### Examples
* `man echo`
* `man clear`
* `man man`
* `man mkdir`

## su

#### Description
Is used to become another user durgin a login session.

#### Options

#### Examples
* `su foo`
* `su bar`
* `su root`

## sudo

#### Description
Allows a permitted user to execute a command as the superuser or another user, as specified by the secutiry policy.

#### Options

#### Examples
* `sudo mv ~/sample.sh /usr/bin`

## passwd

#### Description
Changes passwords for user accounts.

#### Options

#### Examples
* `passwd` - changes the user password
* `sudo passwd` - changes the root password
