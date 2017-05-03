# git

## 创建本地版本库

~~~shell
$ mkdir gitfile
$ cd gitfile
$ git init
~~~

## 文件操作

gitfile`目录下创建文件file01.txt

~~~shell
$ git add file01.txt
$ git status
$ git commit -m "1.创建文件"
~~~

## 分支管理

查看所有分支

~~~shell
$git branch
~~~

创建分支

~~~shell
$git branch dev
~~~

切换分支

~~~shell
$git checkout dev
~~~

提交指定分支

~~~shell
$git push origin dev
~~~

创建分支dev 并切换到dev分支

~~~shell
$git checkout -b dev
~~~

将dev分支合并到当前支

~~~shell
$git merge dev
~~~

删除分支

