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

- Firewall has been configured to only listen to ports 2200, 80 and 123.
- SSH Key Pair authentication is required, password auth is disabled.
- Remote root user login is disabled.
- WSGI Applications are running and have access to a database using PostgreSQL.
- System is being kept up to date with lates package/kernel updates.

## Notice

This server will only be available for grading until 15/09/2018
