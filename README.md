# ansible

#In case of Older OS use this commans (export LC_ALL=C)

#In case pid does not work<br>
sudo apt-get remove --purge python-pip<br>
sudo apt-get autoremove<br>
sudo rm -f /usr/local/bin/pip<br>
sudo easy_install pip==20.3.4<br>
pip --version<br>

**Steps to install Ansible, python3, pip and boto**
sudo apt install ansible
sudo ansible --version
sudo apt install python3-pip
pip install boto
aws configure (Create a user with EC2 full access and configure it in machine)
