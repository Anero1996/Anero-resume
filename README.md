# Anero-resume-
It is a resume for Specialist of anti-money laundering 
$ mkdir  resume && cd resume    ;;创建一个目录来操作
$ git init     ;;创建一个git库
$ git config  --global  user.name "your name"   ;;创建库的ownner，可选
$ git config --global user.email "your email"   ;;创建库的ownner 的email联系方式，可选


$ wget http://labfile.oss.aliyuncs.com/courses/624/cv-template.zip     ;;下载模板简历
$ unzip cv-template
$ mv cv-template/* .
$ rm -rf cv-template* __MACOSX*


使用浏览器打开，你可以编辑你所需的地方，编辑之后，可以打开浏览器的源码查看器，此处以火狐为例

法1：打开菜单-->开发者-->查看器，将鼠标点中<html>标签，点击右键，找到 复制外部HTML  ，单击它，创建一个新文件index.html，粘贴复制的内容，替换掉原来的index.html文件

法2：github仓库直接修改，还可以同时看修改提交后的效果，更加快速

接下来，完成下面的操作你就可以在github上看见部署的项目了。


$ git add .                             ;;追踪resume目录下的所有文件
$ git commit -m 'xzy resume'            ;;提交文件到本地仓库，-m是指定此次提交的message信息，自己改写
$ git remote add origin 远程仓库地址      ;;远程仓库地址，在创建好空的库时可以看见，图三中的https://github.com/xzy256/resume.git
$ git push -u origin master             ;;提交到远程操作
