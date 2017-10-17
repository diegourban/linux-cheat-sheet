# Search

* [grep](#grep) - print lines matching a pattern
* [locate](#locate) - find files by name
* [which](#which) - locate a command
* [find](#find) - locate a command

## grep

#### Description
Searches the name input file(s) for lines containing a match to the given pattern.

#### Options

#### Examples
* `grep somethingToFind whereTofind.txt`

## locate

#### Description
Reads one or more databases prepared by updatedb and writes file names matching at least one of the pattern(s) to standard output.

#### Options

#### Examples
* `locate firefox`
* `locate gedit`
* `locate -i gEdIt`

## which

#### Description
Returns the pathnames of the files(or links) which would be executed in the current environment.

#### Options
* `-i` - file name ignoring case

#### Examples
* `which firefox`

## find

#### Description
Searches for files in a directory hierarchy

#### Options
* `-name` - file name 
* `-iname` - file name ignoring case

#### Examples
* `find / -name pagamentos` - find files with name equals to pagamentos
* `find / -name pagamentos.csv` - find files with name equals to pagamentos.csv
* `find / -iname pagamentos.csv` - find files with name equals to pagamentos.csv ignoring case
* `find / -iname pagamentos*` - - find files with name equals to pagamentos + anything else (regex)
* `find /compartilhamento/financeiro -iname *pagamento*` - find files in a specific folder
