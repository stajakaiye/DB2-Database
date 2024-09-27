# Ansible Playbook for Java upgrade 

This reposistory contains an ansible playbook for IBM DB2 Java upgrade

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

During the execution Ansible Tower will show output


