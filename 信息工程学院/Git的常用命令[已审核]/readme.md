# Git常用的命令

- git init

    `git init`是在当前目录下创建一个新的Git仓库（通过生成.git隐藏目录来存储管理版本所需信息）的命令。

- git add .

    `git add.`是将当前目录及其子目录下所有文件的变更（新增、修改、删除）添加到Git暂存区的命令。

- git commit -m "init"

    `git commit -m "init"`是一个Git命令，用于将暂存区中的文件变更创建一个新的提交（commit），并添加一条注释“init”来简要描述这次提交的内容，从而记录项目在某个特定时刻的状态变化并存入本地仓库。

- git push

    `git push`是将本地仓库的提交推送到远程仓库的命令。

- git fetch

    `git fetch`是从远程仓库获取最新提交、引用和对象等信息，但不自动合并到本地分支的Git命令。

- git pull

    `git pull`是从远程仓库获取最新代码更新并合并到本地当前分支的命令，相当于`git fetch`加`git merge`。

- git config --global user.name "Your Name"

    `git config --global user.name "Your Name"`是设置全局Git提交用户名的命令。

- git config --global user.email "your@email.com"

    `git config --global user.email "your@email.com"`是用于设置全局Git用户邮箱（会应用于所有本地Git仓库）的命令，邮箱用于标识提交者和关联代码托管平台账号。