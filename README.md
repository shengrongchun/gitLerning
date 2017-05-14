每次push到远程库都要输入用户名和密码？


在添加远程库的时候使用了https的方式。。所以每次都要用https的方式push到远程库，速度还慢。。

查看使用的传输协议：

git remote -v
重新设置成ssh的方式：

git remote rm origin
git remote add origin git@github.com:username/repository.git
git push -u origin master