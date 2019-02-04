# Section 3.10 - EC2 Lab

The following commands were ran to apply the latest patches and get a basic site up and running:

```
## Get latest patches
yum update -y

## Install Apache
yum install httpd -y

## Start web server
service httpd start

## Ensure httpd service starts again whenever rebooted
chkconfig httpd on

## Check the service status
service httpd status

cd /var/www/html
```
