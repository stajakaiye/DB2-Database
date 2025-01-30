# Ansible Playbook for Below Task

1. Java upgrade 
2. DB2 start and stop 
3. Java upgrade pre check 
4. DB2 fix pack special patch install 
5. DB2 fix pack special patch uninstall
6. LDAP password change
7. DB2 SSL certificate renew
   

This reposistory contains an ansible playbook for IBM DB2 for above task

### Prerequisites 
Before running the playbook ensure below

Java dump should placed on DB2 server 

This playbook prompt for below variable\
#jdk_binary_location: "Enter the files system path eg. /tmp "\
jdk_binary_location: /tmp

Running the playbook in Ansible Tower\
Go to ansible tower using below url\
https://anssttow01.abcbs.net/#/projects

Find template name "Java_Upgrade_Template" ---> Click the Launch button and then enter jdk_binary_location: <enter dump location on db2 server>  --> next -->Launch

During the execution Ansible Tower will show output in jobs


