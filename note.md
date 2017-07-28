# 流行框架

## ssh方式上传代码
- 公钥 私钥，两者之间是有关联的。
- 生成公钥 ， 和私钥
	ssh-keygen -t rsa -C "邮箱"



 1、
 git pull '地址'  master(分支)



 2、通过 remote 下载到本地

 git remote add 变量  地址  变量和地址相绑定

 git push origin master  地址用 origin代替

 git push origin -u master 把当前的master分支，提交到远程的master分支

 当我们在push时，加上-u参数，那么在下一次push的时候，我们只需要写上 'git push'就能上传我们的代码





































