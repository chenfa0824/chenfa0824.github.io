[个人博客](https://chenfa0824.github.io/blog/)
新建github项目，点击右上角，导航栏目中的 创建按钮+ ，点击New repository，创建一个新的仓库。repository name仓库名称中我们填写
用户名.github.io，用户名就是Owner里边的内容。
⚠️注意：项目名称一定要是 用户名.github.io
git clone https://github.com/chenfa0824/1031.git
git add . （注：别忘记后面的.，此操作是把Test文件夹下面的文件都添加进来）
git commit -m "first commit " （注：“提交信息”里面换成你需要，如“first commit”）
git push -u origin main（注：此操作目的是把本地仓库push到github上面，此步骤需要你输入帐号和密码）

[利用github搭建个人博客](https://blog.csdn.net/weixin_41201231/article/details/142594777)
[Hexo+GitHubPages搭建个人博客](https://blog.csdn.net/middle_age666/article/details/141160238)

[docsify官方文档](https://docsify.js.org/#/zh-cn/quickstart)
[docsify快速部署搭建个人知识库（支持本地、服务器、虚拟机运行）](https://blog.csdn.net/qq_62982856/article/details/129940209)
[工具--docsify详解](https://blog.csdn.net/liyou123456789/article/details/124504727)
[使用docsify+github建立个人网站](https://www.jianshu.com/p/91f7a87301df)
[30分钟使用Docsify+Github Pages搭建个人博客](https://blog.csdn.net/zls365365/article/details/122995130)
[使用git生成SSH公钥，并设置SSH公钥](https://blog.csdn.net/m0_64284147/article/details/139159980)
[手把手教你GitHub 配置 SSH密钥](https://blog.csdn.net/KRzzZzz/article/details/140536430)

初始化项目
docsify init
启动项目
docsify serve

git 提交到远程仓库
要将本地的更改提交到远程仓库，你需要执行以下步骤：
初始化本地仓库（如果尚未完成）：
git init
添加文件到暂存区：
git add .
提交更改到本地仓库：
git commit -m "Your commit message"
添加远程仓库地址（如果尚未添加）：
git remote add origin <remote_repository_URL>
将本地的更改推送到远程仓库：
git push -u origin master
如果你是第一次推送到远程仓库，并且远程仓库不为空（比如有README.md），你可能需要先拉取远程仓库的更改：
git pull origin master
然后解决可能出现的合并冲突，再次提交并推送。
注意：如果你使用的是其他分支而不是master分支，请将master替换为相应的分支名。



                   
原文链接：https://blog.csdn.net/xinnian_yyds/article/details/140573059

[](https://ysgstudyhards.github.io/Docsify-Guide/)