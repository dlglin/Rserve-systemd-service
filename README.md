# Rserve-systemd-service
A service unit for starting and stopping the Rserve binary server using systemd
This assumes that you have [R](https://www.r-project.org/) and [Rserve](https://www.rforge.net/Rserve/) installed.
Simply save the file rserve.service in the /usr/lib/systemd/system/ directory, then you can use `systemctl start rserve`
to start the R server, and `systemctl stop rserve`
to stop the R server.
