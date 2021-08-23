

####################### ![image](https://user-images.githubusercontent.com/84157053/130389799-65c28d60-d7d6-4361-b1a1-8fca1c500555.png)  ############################

# TASK 1

+ Use dynamic inventory for below task, and build the environment with curl command: 
+ Create a playbook to install mariadb server on ubuntu, and adds users to amazon instances:
	1. Bob 
	2. ben 
	3. lisa
	4. katty
+ with their ssh-keys generated for future use. Mariadb should only be restarted on ubuntu servers if the package is installed. Each user should get the following csv file in their home directory  https://people.sc.fsu.edu/~jburkardt/data/csv/addresses.csv
+ Please utilize get_url 


# Issues had on this Task:

1. The hardest part was figuring out how to install MariaDB to Ubuntu, it also needed python-pycurl. For Amazon/Centos works normally the way Farrukh showed in ansible class3.
2. Generating SSH key on Ubuntu machines - after resolving issue with MariaDB it was resolved by itself.
3. /etc/skel  - took long to figure out how to add url to users directories.. good to know.. http://www.linfo.org/etc_skel.html 
4. Started working with Ansible I started loving Hashicorp HCL more and more.. YAML script is such a heart pain.. is there any auto-complete or auto-correct?! :(
5. Tried multiple way of adding multiple users ( as well as variables) none of worked, onlt single ones..


