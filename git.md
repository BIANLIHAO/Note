**2018/11/15**

* git add     添加修改到缓冲区
* git commit -m "xxxx" 将修改添加至工作区，并以xxx命名为此次修改
* git status 查看仓库当前状态
* git diff  “文件名”    查看修改的的内容
* git log    查看提交日志
* git reset --hard commit_id     回退之前的版本（git reset --hard 09ea）
* git reset --hard HEAD^   回退到上一个版本(**HEAD代表指向master分支的指针** ^^代表上上个版本，HEAD~100代表上100个版本)
* git reflog   记录每一次命令
* git status 查看暂存区的状态，这里务必需要先add后commit，如果不add，修改后的版本将不会提交至暂存区
* git checkout  --file  当修改的文件没有被add时可以将文件回退至上一个版本。
* 当发生删除时，如果确定要删除一个文件在rm file后 git rm file.name来删除暂存区的文件，如果需要恢复则git checkout --file 来恢复。



**2018/11/16**

* git remote add origin git@server-name:path/repo-name.git  本地库关联远程看(本地库先git init)
* git push -u origin master  第一次推送master分支的所有内容
* git push origin master 推送最新修改
* 在进行修改后，需要将代表先git add .然后git commit -m "备注"到暂存区，之后将修改push到远端。









