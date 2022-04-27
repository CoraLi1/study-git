# study-git

git 常用指令

git add . --- 加入暂存区

git status ---- 查看状态

git log --- 查看日志

git pull --- 拉远程分支

git push 拉取远程分支

git fetch 拉取远程分支

git clone [ssh密钥](https://www.cnblogs.com/ygfsy/p/13921892.html)

git merge 合并分支

git reset --soft <commit>

git reset HEAD^ # 回退所有内容到上一个版本 
git reset HEAD^ hello.js # 回退 hello.js 文件的版本到上一个版本 
git reset 052e # 回退到指定版本

HEAD 表示当前版本
HEAD^ 上一个版本
HEAD^^ 上上一个版本
HEAD^^^ 上上上一个版本

可以使用 ～数字表示HEAD~0 表示当前版本
HEAD~1 上一个版本
HEAD^2 上上一个版本
HEAD^3 上上上一个版本
以此类推...

取消缓存 Git reset HEAD hello.js

--soft 参数用于回退到某个版本：

--hard 参数撤销工作区中所有未提交的修改内容，将暂存区与工作区都回到上一次版本，并删除之前的所有信息提交：


git revert <commit id>


sdfsdf
