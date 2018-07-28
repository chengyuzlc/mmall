添加文件
git add. 

查看添加的文件状态
git status

上传到本地
git commit -am 'first commit init project'

连接到远程项目地址
git remote add origin git@github.com:chengyuzlc/mmall.git

若报错 fatal: remote origin already exists.

先执行 $ git remote rm origin
 
再执行 git remote add origin git@github.com:chengyuzlc/mmall.git

最后上传文件  git push -u origin master
