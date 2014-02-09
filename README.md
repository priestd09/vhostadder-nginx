vhostadder
==========

Adding virtualhost to apache2

Requirements:
 -  You must have root privileges.
 -  You must have apache2 installed
 -  You must have www-data as apache user
 -  you need to make directory /home/www and make www-data owner

Install instructions:
 -  Put addsite to /bin folder
 -  chmod +x addsite 

Usage:
addsite foobar.org
 - That makes new vhost for domain foobar.org
 - That makes new directory for each domain
