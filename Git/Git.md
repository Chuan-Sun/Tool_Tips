![[Git命令关系.png]]

GUI 更方便

## 创建仓库命令
`git init`
建立 Git 仓库
例：`git init newrepo`，新建一个名为 newrepo 的 Git 仓库

`git clone`
克隆 Git 仓库
例：`git clone repo directory`，把 repo 克隆到 directory

## 配置
`git config`
例：
`git config --list`，显示 Git 配置信息
`git config -e`，针对当前仓库，编辑 Git 配置文件
`git config -e --global`，针对系统上所有仓库，编辑配置文件

## 提交与修改
`git add`
添加需要纳入版本控制的文件
例：`git add *.py*`，将目录下以 .py 结尾的文件纳入版本控制

`git commit`
写入本地仓库
例：`git commit -m "提交说明"`

## 远程操作
`git pull`

`git push`

`git remote`

`git fetch`

## 分支管理
`git branch`
创建分支

`git checkout`
切换分支

`git merge`
合并分支

## 标签
`git tag`