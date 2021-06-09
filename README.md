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
### 打开Git-Bash，输入以下命令，然后一直回车和按【y】即可：
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

# 使用命令行打开文件夹并显示
### explorer
### 在运行中输入命令：
### d:\test..\
### 或者在命令提示符里面输入:
### explorer c:\files\(绝对路径)
### explorer files (相对路径)
### start d:\test..\
### explorer和start的区别是
### start必须使用绝对路径，
### explorer既可以使用绝对路径也可使用相对路径。
### 即可以打开指定的文件夹，并可以在文件夹内操作，和一般文件夹一样
