# zk-training

Zookeeper training VM.

##Installation
```
~$ sudo visudo
ubuntu  ALL=(ALL) NOPASSWD: ALL

~$ sudo apt install -y git
~$ git clone https://github.com/jorisdevrede/zk-training.git
~$ cd zk-training
~/zk-training$ ./install-ansible.sh
~/zk-training$ ansible-playbook -i hosts setup.yml
```
