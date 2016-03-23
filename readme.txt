git config --global user.name "F1"
名称
git config --global user.email "827944@qq.com"
邮箱

git init
仓库

ls
目录
ls -ah
隐藏目录

git add file.txt
添加到仓库
git commit -m "说明"
提交说明

git status
仓库状态

git diff file.txt
修改差别 difference

git log
日志
git log --pretty=oneline
日志一行显示

git reset --hard HEAD^
版本回退

git reflog
命令记录

git diff --cached
暂存区缓存

cat file.txt
查看文件内容

git checkout -- file
撤销修改--回到最近一次commit状态

git reset HEAD file
清除暂存区

git rm file
删除文件

git merge
合并分支

git branch <name>
创建分支

git checkout <name>
切换分支

git checkout -b <name>
创建+切换分支

git merge <name>
合并分支到当前分支

git branch -d <name>
删除分支

git stash
储藏

git stash list
查看储藏

git remote add origin git@github.com:nice2meu/git.git

git branch
查看分支

rm -rf .git
删除.git
git config --global core.autocrlf false
禁用自动转换