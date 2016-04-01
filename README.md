# Ansible-LAMP
Ansible script to create LAMP servers

Role Name
------------

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

Created by Gerhard Pegel
-------

Monitoring Engineer at Wehkamp, the Netherlands. Before joining Wehkamp, I was a sysAdmin at Innovadis & Indenty. I started my career working at a production plant as a junior system engineer. Loves to talk about DevOps, System Administration, Scalability, High Availability, Monitoring tools like Zabbix. Apart from work, I love to meet people, listening to music and watch sports.
