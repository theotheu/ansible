# Requirements
Ansible
Run on your local laptop:

`sudo easy_install pip`

`sudo pip install ansible --quiet`

More info at https://devopsu.com/guides/ansible-mac-osx.html

Security
On your local laptop, copy the content from `~/.ssh/id_rsa.pub`
On your remote host, paste the content into `<username>/.ssh/authorized_keys`

# Configuration
Adjust the variables in `group_vars > all`

# Installation
Run `ansible-playbook -i hosts site.yml`
