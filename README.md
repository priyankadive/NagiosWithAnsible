# NagiosWithAnsible
Ansible playbook to install nagios on ubuntu 14.04.
run playbook with
ansible-playbook -i host.txt main.yml -u username -s -k
After completion check nagios on browser.
http://IP-of_localhost/nagios/
Go to hosts.
It will show us status of localhost.
