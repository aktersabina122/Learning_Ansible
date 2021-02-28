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
![1](https://user-images.githubusercontent.com/33559730/109403851-47809e00-792e-11eb-8776-acd36c8de558.png)
 


# What is Ansible playbook:
An Ansible® playbook is a blueprint of automation tasks—which are complex IT actions executed with limited or no human involvement. Ansible playbooks are executed on a set, group, or classification of hosts, which together make up an Ansible inventory. 

<img width="462" alt="2" src="https://user-images.githubusercontent.com/33559730/109403873-962e3800-792e-11eb-9544-afb9a0bc6077.png">

	All playbook is written in Yml format.
	It starts with –
Example:

<img width="382" alt="3" src="https://user-images.githubusercontent.com/33559730/109403894-d392c580-792e-11eb-81ef-fed57da7a275.png">

 
Explain: How to map with the server?
Replace localhost with the server I need to attach.
Play1 is basically checking the data
Play2 is basically installing httpd and start the server
	Here is 3 task i.e:command (checking data), yum(install httpd) and service httpd (start)
