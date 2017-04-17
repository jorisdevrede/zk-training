# zk-training

Zookeeper training VM. Assumes a clean Ubuntu Desktop 16.04 LTS installation with an ubuntu default user. Ubuntu Desktop can be downloaded here: http://releases.ubuntu.com/16.04/ubuntu-16.04.2-desktop-amd64.iso

## Installation
```
~$ sudo visudo
ubuntu  ALL=(ALL) NOPASSWD: ALL

~$ sudo apt install -y git
~$ git clone https://github.com/jorisdevrede/zk-training.git
~$ cd zk-training
~/zk-training$ ./install-ansible.sh
~/zk-training$ ansible-playbook -i hosts setup.yml
```
