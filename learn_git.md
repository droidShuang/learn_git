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

创建分支dev 并切换到dev分支

~~~shell
$git branch dev
$git checkout dev
~~~

上面的操作也可以精简为

~~~shell
$git checkout -b dev
~~~

