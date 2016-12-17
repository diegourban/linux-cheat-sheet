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

## kill

#### Description
The default signal for kill is TERM. (terminate)

#### Options`
* `-9` - kill the process without terminating it

#### Examples
* `kill 123` - kills the process with id 123
* `kill -9 123` - kills the process with id 123 without terminating it
