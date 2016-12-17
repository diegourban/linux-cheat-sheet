# Process Management

* [ps](#ps) - report a snapshot of the current processes
* [kill](#kill) - send a signal to a process
* [top](#top) - display linux processes
* [killall](#killall) - kill all processes by name
* [pstree](#pstree) - display a tree of processes
* [jobs](#jobs) - list the jobs
* [bg](#bg) - send a job to the background
* [fg](#fg) - send a jog to the foreground
* [cmd](#cmd) - runs a command

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
* `killall firefox` - kill all the firefox processes
* `kill -9 top` - kill all the process with name top without sending a terminate signal


## pstree

#### Description
Shows running processes as a tree.

#### Options

#### Examples
* `pstree`

## jobs

#### Description
List the jobs

#### Options

#### Examples
* `jobs`

## bg

#### Description
Send a job  from the jobs list to brackgound

#### Options

#### Examples
* `bg 1`

## fg

#### Description
Send a job from t he jobs list to foreground

#### Options

#### Examples
* `fg 1`

## cmd

#### Description
Runs a command

#### Options

#### Examples
* `firefox` - run firefox in foreground
* `firefox &` - run firefox in background
* `gedit &`
