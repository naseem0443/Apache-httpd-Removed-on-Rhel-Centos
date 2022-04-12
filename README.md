# Apache-httpd-Removed-on-Rhel-Centos


)Query and list all the Apache rpm packages<br>
rpm -qa "httpd"
2)List the installed Apache packages.
yum list installed "httpd*"
3)Remove the installed httpd packages
yum remove "httpd*" -y
4)Remove the Document root directory
rm -rf /var/www
5)Remove the Configuration Files
rm -rf /etc/httpd
6)Remove the Supporing files and httpd modules
rm -rf /usr/lib64/httpd
7)delete the Apache user
userdel -r apache
8)check the apache user in /etc/passwd location.
grep "apache" /etc/passwd
9)Check the status of Apache server
systemctl status httpd
