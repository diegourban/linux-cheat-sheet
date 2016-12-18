# service commands

* `service` - run a System V init script

Runs a System V init script or upstart job in as predictable an environment as possible, removing most environment variables and with the current working directory set to /.

* `service [service name]  start` - to start a service
* `service [service name]  stop` - to stop a service
* `service [service name]  status` - to show the status of a service

Under the hood, what happend is:

sudo /etc/init.d/vsftpd stop
sudo /etc/init.d/vsftpd start
sudo /etc/init.d/vsftpd status

/etc/init.d is a script the politely notifies a service to start/stop or show status.
The scripts inside /etc/init.d are programs that will be executed on the startup of the machine.
