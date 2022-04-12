# Apache-httpd-Removed-on-Rhel-Centos


)Query and list all the Apache rpm packages<br>

rpm -qa "httpd"<br>

2)List the installed Apache packages.<br>

yum list installed "httpd*"<br>

3)Remove the installed httpd packages<br>

yum remove "httpd*" -y<br>

4)Remove the Document root directory<br>

rm -rf /var/www<br>

5)Remove the Configuration Files<br>

rm -rf /etc/httpd<br>

6)Remove the Supporing files and httpd modules<br>

rm -rf /usr/lib64/httpd<br>

7)delete the Apache user<br>

userdel -r apache<br>

8)check the apache user in /etc/passwd location.<br>

grep "apache" /etc/passwd<br>

9)Check the status of Apache server<br>

systemctl status httpd<br>
