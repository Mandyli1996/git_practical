this is the hello world

Day 1
初始化一个Git仓库，使用git init命令。

添加文件到Git仓库，分两步：

使用命令git add <file>，注意，可反复多次使用，添加多个文件；
使用命令git commit -m <message>，完成。



Day 2
要随时掌握工作区的状态，使用git status命令。

如果git status告诉你有文件被修改过，用git diff可以查看修改内容。


Day 3
HEAD指向的版本就是当前版本，因此，Git允许我们在版本的历史之间穿梭，使用命令git reset --hard commit_id。
HEAD^ AND HEAD~100

穿梭前，用git log可以查看提交历史，以便确定要回退到哪个版本。--
git log --pretty=online
要重返未来，用git reflog查看命令历史，以便确定要回到未来的哪个版本

Day 4

暂存区是Git非常重要的概念，弄明白了暂存区，就弄明白了Git的很多操作到底干了什么。

没弄明白暂存区是怎么回事的童鞋，请向上滚动页面，再看一次。
