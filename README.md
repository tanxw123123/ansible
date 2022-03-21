Ansible安装  
1. 安装  
环境：ubuntu 20.04  
```
$ sudo apt update
$ sudo apt upgrade
$ sudo apt install ansible
$ ansible --version
```
2. 配置秘钥
```
$ ssh-keygen    #生成秘钥对，然后将公钥拷贝到远程主机authorized_key
```
