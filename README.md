###注意点
- 执行`git branch -M main` 将当前分支重命名成main

### git 分支操作
- 一个仓库可以有多个分支，默认创建好的仓库有一个默认的main分支，分支是用来存储代码的房间

### 创建新分支
创建新分支`git branch分支名`，注意创建新的分支之前，需要保证已有的分支和远端版本一致，创建好之后可以使用‘git branch
查看本地的所有分支，带·号和颜色的说明当前处于该分支。新创建好的分支，创建的时候里面的内容和 main分支内容一样，可以使用`git
checkout分支名’切换到对应的分支。当你想要将分支推送到远端，  第一次推送的时候，   由于远端并不存在新的分支，需要使用`git push--set-upstream origin分支名`I想远端提交   

`git checkout -b 分支名` 新建分支并切换过去

注意：在哪个分支下操作创新一个新分支，那么这个创建的新分支和这个当前的分支里的内容一样

### 在网上新建一个空仓库 在本地新建一个文件夹和网上空仓库重名 如何做到网上和本地关联
1 git init
<!-- git add README.md
git commit -m "first commit" -->
2 git branch -M main
3 git remote add origin git@github.com:rufeng12345/kongcangku.git
4 git push -u origin main