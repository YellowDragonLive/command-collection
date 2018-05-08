# ubuntu - tencent 
## 设密码 password
sudo passwd root
## 写配置 config
nano /etc/ssh/sshd_config

## 重启 restart
sudo /etc/init.d/ssh restart

## 切换到 root 账户
sudo su