# VirtualBox Guest addition installer 
#Centos6

### Install Ansible on your Sever CentOS 6/7 

``` Make sure you have connection 
sudo yum install epel-release -y 
sudo yum install ansible -y 
ssh-keygen Enter Enter Enter 
```

### Cloning and running the script 
```
git clone https://github.com/farkhodsadykov/virtualbox-guest-additions.git
cd virtualbox-guest-additions/
sh ansible_add_client
```

`Please enter the IP :` Enter your clients ip
`Please enter the version VB :` Enter version of VirtualBox
`Please enter the PASSWORD :` Client's Password `root`
`Please enter the name for ansible :` This name script will use for Ansible connection 


