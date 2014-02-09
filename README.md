vhostadder
==========

Adding virtualhost to apache2

Requirements:
1. You must have root privileges.
2. You must have apache2 installed
3. You must have www-data as apache user
4. you need to make directory /home/www and make www-data owner

Install instructions:
1. Put addsite to /bin folder
2. chmod +x addsite 

Usage:
addsite foobar.org
 - That makes new vhost for domain foobar.org
 - That makes new directory for each domain
