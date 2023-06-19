### 初识Git
Git 是一个分布式的版本管理控制系统，是一种用户可以根据时间追溯项目文件，修改历史和属性的工具。


### Git功能

沙箱

每日备份

异地协同工作

现场版本控制


### Git 用户设置
在第一次使用时， 我们需要设置下git的配置：
- 告诉git当前用户名称和邮件地址

```git
git --version // 检查版本
git config --global user.name "你的用户名"
git config --global user.email "你的邮件"
```

- 设置别名，以便可以使用简洁的命令
```git
git config --global alias.st status 
// git status 相当于 git st

git config --global alias.cm commit
```

- 设置系统所有用户别名
使用 sudo 管理权限可以给当前系统上所有git用户设置别名
```git
sudo git config --system alias.st status
```


### Git 指令
初始化
进入目标文件夹执行 git init 指令创建版本库 (.git目录)，版本库会保存在当前工作区中，位于隐藏文件夹 .git 的子目录下
```git
git init
```

git config
在之前出现的git config命令中，有的使用了 --global参数，有的使用了 --system参数，




git commit
提交到本地仓库中


git push origin  master
提交到远程仓库







在git 命令中开启颜色显示 
```git
git config --global color.ui true
```























### Github 远程仓库

 
