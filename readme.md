Git is a distributed version control system.
Git is free software distributed under the GPL.
Git has a mutable index called stage.
Git tracks changes of files.
Wuhu,i just did it successfully first time!

## Start a new git repo in origin and local:
* [廖雪峰git---添加远程库](https://www.liaoxuefeng.com/wiki/896043488029600/898732864121440)
* [github绑定---将本地git仓库绑定刚创建的github远程仓库](https://blog.csdn.net/yanlaifan/article/details/111366324)
* [github 配置使用 personal access token 认证](https://segmentfault.com/a/1190000040544939)
* git bash中使用http首次绑定时会需要token验证并报错，随后的输入登录名时，输入**完整GitHub账号"@"之前**的**用户名称**，**登录密码也填token**，而不是登录密码！

## Error occur in Git
``` error: could not open '.git/rebase-merge/git-rebase-todo': No such file or directory```
> git分支后面出现"|REBASE"
* `git rebase --abort`将当前进行到一半的rebase取消-----[git分支名称后面多出REBASE解决](https://blog.csdn.net/Small_Lee/article/details/82150794)
 
```fatal: Authentication failed for 'https://github.com/xiayitian1003/Working-Tools.git/'```
>git push 发现token过期
>重置登录信息,刷新出登录框,输入更新token有效期:头像-->settings-->Developer settings-->Personal acess tokens
* [git操作及fatal: Authentication failed for错误解决](https://blog.csdn.net/u011394598/article/details/80256896)

>如何修改历史commit的代码更改内容
* [git rebase修改历史提交内容](https://www.cnblogs.com/oloroso/p/9723783.html)

>如何不commit又保存未完成的更改，从而可以切到其他分支进行开发后又切回来复原现场
* [git-stash用法小结](https://www.jianshu.com/p/1c7ecc8d3dfb)
