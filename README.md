# ubuntu-tencent 
# 设密码
 sudo passwd root

nano /etc/ssh/sshd_config
// 写配置
sudo /etc/init.d/ssh restart
// 重启
sudo su
//切换 root 账号
安装 asm.js
用 sdk 先装window 下有不同的指令
c 的静态有多种数据类型 位操作补一下
On Windows, run emsdk instead of ./emsdk, and emsdk_env.bat instead of source ./emsdk_env.sh.
Command	Details
sails generate model	Generate api/models/Foo.js, including attributes with the specified types if provided.
sails generate action	Generate a standalone action.
sails generate helper	Generate a helper at api/helpers/foo.js.
sails generate controller	Generate api/controllers/FooController.js, including actions with the specified names if provided.
sails generate hook	Generate a project hook in api/hooks/foo/.
sails generate generator	Generate a foo folder containing the files necessary for building a new generator.
sails generate response	Generate a custom response at api/responses/foo.js
sails generate adapter	Generate a api/adapters/foo/ folder containing the files necessary for building a new adapter.
sails generate sails.io.js	Generate a sails.io.js file at the specified location, overwriting the default sails.io.js if applicable.
sails generate api	Generate api/models/Foo.js and api/controllers/FooController.js.
sails generate new	Alias for sails new.
sails generate etc	Experimental. Adds the following files to your app:
• .gitignore 
• .jshintrc 
• .editorconfig 
• .npmignore 
• .travis.yml 
• .appveyor.yml
# 打包exe文件
 gcc -o crc32 crc32.c
 ./crc32
 
 
 
#显示当前 的git配置
git config --list

#编辑git配置
git config -e [--global]

# 设置提交代码时的用户信息
git config [--gloal] user.name "[name]"
git config [--gloal] user.email "email address"

