Vhost
========
Install:
-----------

curl https://raw.githubusercontent.com/kbirmhrjn/vhost/master/script.sh > vhost

chmod guo+x vhost

sudo mv vhost /usr/local/bin

Usage:
-----------

**syntax:**
sudo vhost -d 'directory' -s 'server-alias'

**example:**
sudo vhost -d /vagrant/new-project  -s new-project.local

**help:**
vhost -h
