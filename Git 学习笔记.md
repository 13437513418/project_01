# Git 学习笔记

## 	获取仓库方式

​			git init 



## 	查看文件状态

​			git status  简写：git status -s



## 	跟踪新文件放置暂存区

​			git add 文件名



## 	添加至git仓库

​			git conmit -m  -m "对文件进行描述"



## 	撤销对文件的修改

​			git checkout --文件名



## 	从暂存区移除

​			git reset HEAD 文件名



## 	从git仓库移除

​			git rm -f 文件名  从git仓库和工作区移除

​			git rm --rached 文件名 从git仓库移除![image-20230225231908563](C:\Users\20591\AppData\Roaming\Typora\typora-user-images\image-20230225231908563.png)

![image-20230225231655466](C:\Users\20591\AppData\Roaming\Typora\typora-user-images\image-20230225231655466.png)



## 	查看历史提交

​			git log 

​			git log -2 

​			git log -2 --pertty = online    一行显示



## 	回退指定版本

​			git log --pretty = online

​			git reset --hard <版本号>

​			git reflog --pretty = online 查看全部版本

​			