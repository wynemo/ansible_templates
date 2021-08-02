## 添加公钥到目标机器

例子：添加csj.pub 公钥到 ci_hosts里的机器

`ansible-playbook -i hosts upload_ssh_keys.yml --extra-vars "pub_key=id_rsa.pub"`

