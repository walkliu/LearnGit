hello world , git is back
you have learn 
vi 文件名  %创建文件
git add 文件名  %添加文件到版本库
git commit -m "说明" %提交文件

git status %查看文件状态
git diff 文件名 %查看文件修改的地方

git commit -m "append GPL" %将文件保存为一个快照，以防丢失或误删

git log %查看最近三次的提交
git log --pretty=oneline %查看最近三次的提交文件的commit id

git reset --hard HEAD^ %例如有1 2 3版本，3版本为最新版本，则该操作退回到2版本 有两个^^,标识退回到1版本，若要退回到前第100个版本，可用~100

cat 文件名 % 查看文件内容

git reset --hard (commit id 前五位即可) %版本回退或者前进
但有时候并不知道commit id 这时可以运行

git reflog  查看命令
