# Ansible Documentation

The full breakdown of the process and reasoning will be under the wiki tab

However, to run the playbook first you should have Ansible already installed on your machine/device

Download the `project0_lamp.yml` file on to that device, or copy/paste it into your own text editor on your machine. 

For this example, I am assuming you copy/pasted the `project0_lamp.yml` file and renamed it

Run the command (as root)
`ansible-playbook --connection=localhost <name of your file>.yml`

If not root then do 
`sudo ansible-playbook --connection=localhost <name of your file>.yml`

This playbook should create and run a LAMP webserver with our index page, feel free to change the repo link in the git clone section to your own repo. 

##### Note, this file works for both Centos and Ubuntu, however for Ubuntu, the TLS/SSL portion needs a cert and a private key. If you do not want TLS/SSL on your server, comment out that section.





