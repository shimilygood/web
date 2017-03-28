# 网站托管web   网址：http://shimilygood.github.io/web
## 步骤
* 1.在GitHub上新建一个repository目录

* 2.在本地相应的文件目录打开命令行窗口或者git bash窗口

* 3.初始化git ,创建一个git文件

*   git init

* 4.添加文件到git仓储

*   git add .

* 5.添加备注：
*   git commit -m "first commit"
* 6.关联路径：
*    git remote add origin git@github.com:shimilygood/web.git

* 7.先上传到master分支上：git push -u origin master

* 8.创建可以预览网页的分支gh-pages

*   git branch gh-pages

* 9.切换到gh-pages分支

*    git checkout gh-pages

* 10.查看分支

*  git branch

* 11.上传到gh-pages分支上
*  git add .
*  git commit -m 'web'
*  git push -u origin gh-pages

* 12.预览地址：http://shimilygood.github.io/web

# shimilygood.github.io如果以这个为GitHub目录，master分支也可以直接被预览
