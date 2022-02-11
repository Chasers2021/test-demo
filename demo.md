git init 初始化
git add 加入暂存区
git commit -m提交到本地
git status 查看项目状态
git branch 'name' 创建分支
git checkout 'branch name'切分支
git branch -d 'branch name'删除分支
git checkout -- '文件名' 回到上一次提交的状态
git checkout 'id' -- '文件名' 将指定文件回到指定版本
git reset --HEAD '文件名'  撤销追踪
git reset --hard 'id' 回到指定版本

git remote add origin '地址'关联远程仓库
git push -u origin master 上传远程仓库

git log 查看提交记录
git log -p '文件' 查看某个文件的具体操作
git show id 查看具体的修改内容
git log --pretty=online '地址'查看某个文件的提交内容
git log --author 'xx' 查看某个人的提交记录


git config --global user.name  配置用户名
git config --global user.email 配置邮箱






