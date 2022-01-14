# Services:-
- Once We Have succesfully installed a Software in Servers. Especially That runs on background such as Webservers and Database Servers We need to make sure 
  that the server or Services are running Even after the sysytem Rebooted
- Services in linux Help you configure software to run in background and make sure that they are running even after system are rebooted.As well as they follow 
  right order of startup
- When any Software that Runs as a service in background is installed Such As web server / Database server Or DevOps Tools like Docker They are Automatically 
  configured as a service in system. 
  
### commands to Start a Service 
```
systemctl start Service-Name
```
### commands to Stop a Service 
```
systemctl stop Service-Name
```
### check the status of a service
```
systemctl status Service-Name
```
### configure Service for Status as a Service 
```
systemctl enable Service-Name
```
### configure Service to not Status as a Service 
```
systemctl disable Service-Name
```
