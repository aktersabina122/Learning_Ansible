# Learning_Ansible
# Ansible:
Ansible is an open-source automation tool, or platform, used for IT tasks such as configuration management, application deployment, intraservice orchestration, and provisioning.
# What is Ansible and how it works?
Ansible works by connecting to your nodes and pushing out small programs, called "Ansible modules" to them. ... Ansible then executes these modules (over SSH by default), and removes them when finished. 

# How to install Ansible in macOs:
brew install ansible

# How to check version:
Ansible –version

# How to check if the installation is successful:
 


# What is Ansible playbook:
An Ansible® playbook is a blueprint of automation tasks—which are complex IT actions executed with limited or no human involvement. Ansible playbooks are executed on a set, group, or classification of hosts, which together make up an Ansible inventory. 

	All playbook is written in Yml format.
	It starts with –
Example:

 
Explain: How to map with the server?
Replace localhost with the server I need to attach.
Play1 is basically checking the data
Play2 is basically installing httpd and start the server
	Here is 3 task i.e:command (checking data), yum(install httpd) and service httpd (start)
