

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

 
 
 
#显示当前 的git配置
git config --list

#编辑git配置
git config -e [--global]

# 设置提交代码时的用户信息
git config [--gloal] user.name "[name]"
git config [--gloal] user.email "email address"

