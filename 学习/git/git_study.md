https://www.bilibili.com/video/BV1wm4y1z7Dg?p=30&spm_id_from=pageDriver&vd_source=15fede687b3c8e571bf980118e321794


创建仓库
git init

克隆仓库
git clone https.......

查看状态 
git status


Add
git add *


Commit
git commit -m 新增文件


恢复误删除文件
git restore a.txt

git log
q   退出


删除后已经commit如何恢复
git log --oneline
git reset --hard 文件版本号
或者
git log --oneline
git restore 提交版本号

创建新分支
git branch 新branch名字

查看现有分支
git branch -v 

切换分支
git checkout 要去的分支名

创建并切换过去
git checkout -b 要创建且切换过去的分支名

删除分支
git branch -d 要删除的分支名

合并分支
git merge 要被合并的分支名


git tag 
git tag -d 

git remote add orgin 



















