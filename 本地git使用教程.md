# GitHub学习笔记

```shell
#最开始的配置
git config --global user.name "用户名"
git config --global user.email "邮箱"

#跳转到目标文件夹下
git init

#查看文件状态
git statius 文件名

#查看文件更改情况
git diff 文件名

#添加到暂存区
git add 文件名

#上传到本地库里
git commit -m "注释"

#查看提交版本历史
git log

#跳转到指定的历史版本
git reset --hard HEAD~跳的版本数

#记录历史版本
git relog

#修改了文件但是没有add
git checkout -- 文件名

#add了但是还没有commit，撤销add，重新放回工作区
git reset HEAD 文件名

#删除文件
git rm 文件名

```
