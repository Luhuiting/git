# git
1)	查看git命令信息:	Git 
2)	查看全部git子命令: 	git help –a
3)	逐行查看文件的修改历史	 git blame <file name>
4)	从第100行开始，到110行。逐行查看文件的修改历史:	git blame -L 100,10 <file name>
5)	列出打算清楚的档案: git clean -n
6)	真正的删除: git clean –f
7)	连gitignore中忽略的档案也清除：git clean –x
8)	文件夹内的文件全部添加到暂存区：git add .  
9)	一个文件多次提交：git add –p
