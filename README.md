# 练习使用Git

`git init` 初始化项目，将项目文件变为git上的一个仓库的概念，会多一个.git的隐藏文件夹，需要在项目的根目录下进行。

工作区-->暂存区：`git add -A`	//-A表示全部文件

暂存区-->仓库：`git commit -m "提交信息的备注"`

`VS code` 中可以对git仓库进行操作。

.git文件夹删除，项目成了一个普通的文件夹，历史记录无了。

## 查看历史提交记录

`git log`

## 维护项目日常

工作区文件恢复之前提交的一次状态`git checkout <filename>`

将上一次提交回滚，上次修改的地方会出现在工作区，git仓库会保持在上上次的状态：`git reset HEAD^1`

## 分支

1. 主分支main应该是一个完成态

2. 以当前分支为基础生成分支``git checkout -b <分支名>``
3. 切换分支：`git checkout <分支名>`

4. 合并分支：git merge <分支名>

5. 放弃合并：git merge --abort

6. 查看分支：bit branch

7. 删除分支：bit branch -D <分支名>

## Git和Github仓库

1. 推送：`git push`
2. 拉取：`git pull`

