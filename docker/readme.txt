远程主机(centos7)需要删除firewalld, 关闭selinux并重启，配置好sshd让本地机器可以用ssh登陆

远程主机ubuntu18 要配置好sudo 免密
ansible-playbook docker_ubuntu_18.yml --extra-vars "hosts=10.100.222.13" --extra-vars "https_proxy=http://10.100.222.22:1081"
