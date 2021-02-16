#Episode 1
- Download Vagrant and VirtualBox to get a local environment setup.
##Setting up an environment
This will create a Vagrantfile in which you can configure your environment in.
```shell
vagrant init geerlingguy/centos7
```
Will start your virtual machine.
```shell
vagrant up
```
Gives you SSH access to the VM
```shell
vagrant ssh
```
Help connecting to your VM?
```shell
vagrant ssh-config
```
Stop the VM
```shell
vagrant halt
```
Destroy the VM
```shell
vagrant destroy
```
##Your first playbook
Once you have your Vagrant VM's up, you can configure Vagrant to use your playbook by configuring the Vagrantfile.

Running your playbook, this runs any provision defined in the Vagrantfile
```shell
vagrant provision
```