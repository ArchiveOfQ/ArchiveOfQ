创建新的github库并push，发现用错github账号了。
查看git config --list
STFW并运行以下命令：
git config --global --unset user.name
git config --global --unset user.email
git config user.email "email.com"
git config user.name "ArchiveOfQ"

彻底删除submodule，删除git历史：
rm -rf .git

重新init：
git init

设置用户名和邮箱
git config user.name "ArchiveOfQ"
git config user.email ”email"

设置gitignore：
nano .gitignore
写进去 .DS_store

add，commit，branch，push一气呵成
