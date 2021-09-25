###注意点
- 执行`git branch -M main` 将当前分支重命名成main

### git 分支操作
- 一个仓库可以有多个分支，默认创建好的仓库有一个默认的main分支，分支是用来存储代码的房间

### 创建新分支
`git branch 分支名`创建新的分支之前需要保证其他的分支和远端版本一致
### 在网上新建一个空仓库 在本地新建一个文件夹和网上空仓库重名 如何做到网上和本地关联
1 git init
<!-- git add README.md
git commit -m "first commit" -->
2 git branch -M main
3 git remote add origin git@github.com:rufeng12345/kongcangku.git
4 git push -u origin main