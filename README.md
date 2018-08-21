# linux-config-udacity

## Description

This readme describes everything that was done for the Udacity Linux Configuration project. The server instance was created using Amazon AWS Lighsail.

## Site Information

- IP Address: ```35.178.213.144```
- Item Catalog URI ```/catalog```

## Software Installed

- Ubuntu Linux Distribution
- Python2 and Python3
- Apache2 Web Server
- Python Pip and multiple python modules

## Configuration

The following list describes what configuration changes were made to the server.

- Firewall has been configured to only listen to ports 2200, 80 and 123. This was done using the ```ufw``` firewall program.
- SSH Key Pair authentication is required, password auth is disabled. Additionally the key itself is protected by a passphrase.
- Remote root user login is disabled. To achieve this I used ```nano /etc/ssh/sshd_config``` and set the ```PermitRootLogin``` value to ```no```
- WSGI Applications are running and have access to a database using PostgreSQL.
- System is being kept up to date with latest package/kernel updates. This was achieved using ```sudo apt-get update``` and ```sudo apt-get upgrade```.

## Notice

This server will only be available for grading until 15/09/2018


## Third Party Resources Used

[mediatemple](https://mediatemple.net/community/products/dv/204643810/how-do-i-disable-ssh-login-for-the-root-user) - Tutorial on how to disable root login.
[Ubuntu Help](https://help.ubuntu.com/lts/serverguide/firewall.html.en) - Documentation on ```ufw``` firewall.
[Ubuntu Packages](https://packages.ubuntu.com/) - Searching for packages to install.
