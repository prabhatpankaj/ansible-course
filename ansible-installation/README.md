## -bash: warning: setlocale: LC_CTYPE: cannot change locale (UTF-8): No such file or directory solution

sudo nano /etc/environment

# add these lines...

LANG=en_US.utf-8
LC_ALL=en_US.utf-8

# activate environment

source /etc/environment

sudo yum update

# Ansible can be installed via “pip”, the Python package manager. If ‘pip’ isn’t already available in your version of Python, you can get pip install by running the below command.

sudo su

yum install python-pip

# Ansible also uses the following Python modules that need to be installed:

pip install paramiko PyYAML jinja2 httplib2

# After installation of all pre-requisites and python-pip, then install Ansible with the below command.

pip install ansible



