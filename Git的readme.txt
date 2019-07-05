git init:初始化仓库

1、Git安装之后需要进行一些基本信息设置

　　a、设置用户名：git  config -- global  user.name  '你再github上注册的用户名';

　　b、设置用户邮箱：git  config --global  user.email  '注册时候的邮箱';


2:添加到仓库
git add index.html(cmd命令,要在index.html的目录下)
git add *.html （添加一类文件）
git add . (添加所有文件)


3：查看
git status

4:删除
git rm --cached  文件名

5：提交
git commit(之后还需要输入备注信息)
你也可以(又做了提交也备注了信息)
git commit -m '在此输入备注信息'


6:分支
创建分支: git branch 分支名字
切换分支: git checkout 分支名字
master为主分支
主线只有一个,而分支有很多,
最后只需要将分支的内容合并到主线中就ok
合并分支: git merge 分支名字（只能在主线中做此操作）


7:推送到远程仓库
git remote add origin https://github.com/liujie520/homework.git
再
 git push -u origin master

8：从网络服务器下载到本地
git clone https://github.com/liujie520/homework.git(该操作进入到文件夹中操作即可)

当你克隆之后,文件夹里只有主分支的东西
如果你想看分支里的东西,那么就得用cmd命令进入文件夹里去切换分支
切换完之后,就能看到其他分支的数据了

tip:
当你上传后的文件,你自己又修改了,就又需要使用
git add然后再
git commit -m 进行提交
