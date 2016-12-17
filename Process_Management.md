# Process Management

* [ps](#ps) - report a snapshot of the current processes
* [kill](#kill) - send a signal to a process

## ps

#### Description
Displays information about a selection of the active processes.

#### Options`
* `-e` - all processes
* `-f` - full format listing

#### Examples
* `ps`
* `ps -e`
* `ps -ef`
* `ps -ef | grep firefox` - list all processes, send the list to grep to filter by firefox and print it

## kill

#### Description
The default signal for kill is TERM. (terminate)

#### Options
* `-9` - kill the process without sending a terminate signal

#### Examples
* `kill 123` - kill the process with id 123
* `kill -9 123` - kill the process with id 123 without sending a terminate signal
