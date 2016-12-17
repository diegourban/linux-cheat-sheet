# Process Management

* [ps](#ps) - report a snapshot of the current processes
* [kill](#kill) - send a signal to a process
* [top](#top) - display linux processes
* [killall](#killall) - killall processes by name

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

## top

#### Description
The top program provides a dynamic real-time view of a running system.

#### Options
* `-u` - display only processes with a user id or name matching
* `-p` - monitors only processes with specific process id

#### Examples
* `top`
* `top -a jeremias` - only display jeremias's processes
* `top -p 123` - only display the processe with id 123

## killall

#### Description
Killall sends a signal to all processes running any of the specific commands.

#### Options
* `-9` - kill the process without sending a terminate signal

#### Examples
* `killall firefox` - kill all the processes firefox processes
* `kill -9 top` - kill all the process with name top without sending a terminate signal
