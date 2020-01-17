# first-ansible-playbook

This is a basic ansible playbook that allows installs nginx to be run on an IP address specified in etc/ansible/hosts. This ansible playbook installs the nginx package, and then runs it as a service.

This application needs ansible to run, and it will require PIP in order to install. Installing instructions for PIP can be found here:https://pip.pypa.io/en/stable/installing/ and instructions for installing ansible can be found at the following website:https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html

You will also need to make sure that a file in /etc/ansible/ called 'hosts' exists in order for it to run. If this file does not exist, create the file and add in the ip address(es) you want nginx to run on.

