添加文件到仓库
git add 

提交到仓库
git commit -m"提交描述"

连接仓库
git remote add gitee git@gitee.com:f-two-two/zht.git


查看仓库
git remote -v

删除已有的远程库
git remote rm origin

推送到仓库
git push gitee master

创建并切换到分支
git checkout -b dev

创建分支
git branch dev

切换分支
git checkout dev

查看分支
git branch

合并分支
git merge dev

删除分支
git branch -d dev

创建并切换分支也可以使用
git switch -c dev

直接切换到已有的master分支
git swich master

查看修改记录
git status