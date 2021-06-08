# Git  first use git

# 1、创建本地仓库（必须与github上面创建的仓库名称一样）（git init 命令）
### git init 仓库名称（必须与github创建的仓库名称一样）
# 2、切换到创建的本地仓库（cd 命令）
### cd 仓库名称
# 3、添加远程仓库（git remote add origin 命令）
### git remote add origin 仓库克隆SSh地址
# 4、将分支推送到GitHub（git push 命令）
### 首次推送  git push -u origin master
### 非首次推送 git push

# 生成SSH key并且查看、复制key
### 1、生成SSH key
### 打卡Git-Bash，输入以下命令，然后一直回车和按【y】即可：
### ssh-keygen -t rsa -C "GitHub注册的邮箱账号"
### 生成key后复制命令：clip < ~/.ssh/id_rsa.puh

# vim 命令
### vim 文件名
### 打开文件 cat 文件名 
### a     从光标右侧开始添加正文
### i     从光标左侧开始添加正文
### I     从行首开始添加正文
### o     在当前行之后打开新一行
### O     在当前行之前打开新一行
### x     删除光标所在处的字符
### !q    不保存退出
### !wq   保存退出
### !w    保存
