# readme

--我是傻逼
那你呢？

- 项目说明文档
  1. 一般会随着项目一起生成
  2. 作为项目说明文档

---

## git 的基本操作

1. git init 初始化一个本地版本库 执行完毕后悔生成一个隐藏文件 .git
2. git add 文件名 把当前目录下的某个文件提交到暂存区 git add . 提交当前目录下的所有变动文件
3. git status 查看当前目录状态 包括了新增文件 删除文件 修改文件
4. git commit -m '这是你需要提交的注释信息'
5. git log 查看操作日志
6. git reflog 简单版本的操作日志
7. git reset --hard 版本号 返回到指定的版本(修改的是工作区的文件)
8. git branch 查看分支 当前分支有 \*
9. git branch 分支名 创建分支
10. git checkout 分支名 切换分支

## 本地仓库的三个部分

1. 工作区
2. 暂存区
3. 本地仓库
