Git is a distributed version control system.
Git is free software distributed under the GPL.

使用Git和TortoiseGit进行本地代码和远程代码仓同步
1、下载Git和TortoiseGit
2、生成ssh-key并放入GitHub上
	git config --global user.name "用户名"
	git config --global user.email "邮箱"
	ssh-keygen -t rsa -C "邮箱"
3、使用TortoiseGit
	pull
	commit
	push