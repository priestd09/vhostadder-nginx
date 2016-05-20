vhostadder
==========

Adding virtualhost to Nginx

Requirements:
 -  You must have root privileges.
 -  You must have nginx installed
 -  You must have www-data as apache user
 -  you need to make directory /home/www and make www-data owner

Install instructions:
 -  Put addsite and delsite to /usr/local/bin folder

Usage:
addsite foobar.org
 - That makes new vhost for domain foobar.org
 - That makes new directory for each domain
