# gitskills

1、我们使用当前目录作为git仓库
	git init
     使用指定目录当git仓库
	git init <目录>

2、跟踪文件，最后提交
	git add *.c
	git add READE
	git commit -m ‘'

3、我们使用 git clone 从现有 Git 仓库中拷贝项目
	git clone <拷贝的url>


github和git使用

	本地库已经commit了，git push [alias] [branch] 到某个分支仓库

1、添加到远程服务
	git remote add [shortname] [url]
	
	exp:
		git remote add origin git….git

2、上传到github
	git push -u origin master

3、删除远程仓库
	git remote rm [别名]