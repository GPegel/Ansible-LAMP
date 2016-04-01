# Ansible-LAMP
Ansible script to create LAMP servers

Role Name
=========

LAMP (Linux, Apache, MySQL, PHP)

Requirements
------------

I've created and tested this role to be running on a CentOS version 7 server.
The HTTPD and MariaDB server are being installed on the same server.

If you can't reach the website then it's possible that you need to open port 80 on the server. To do this:

Step 1. ssh to the machine

Step 2. $ sudo firewall-cmd --zone=public --add-port=80/tcp --permanent

Step 3. $ sudo firewall-cmd --reload


How to run the Playbook
----------------

$ ansible-playbook site.yml -i hosts

License
-------

BSD
