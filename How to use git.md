##### 1.  Git配置：
+ ##### Linux:（Ubuntu）

	##### 1.安装git：
```
	 $ sudo apt-get install git
```
##### 2.配置Git信息：
	&emsp; 在下载代码库和上传代码库时git需要提供开发者姓名和邮箱信息，因此需要提前配置
```
$ git config --global user.email yanglei30@jd.com
$ git config --global user.name	Yanglei
```
##### 3.下载代码库：
&emsp; 对远程代码库进行更改，首先要将远程代码库下载到本地，然后进行修改; 首先建立本地git库工作目录，本文以/usr/local/mygit为例，然后进入本地git录工作目录并将远程库下载到本地
``` sh
#创建本地git库工作目录
$ sudo mkdir /usr/local/mygit
#进入工作目录
$ cd /usr/local/mygit
#下载远程git代码库
$ git clone http://source.jd.com/app/sharecode.git
```
##### 4.代码库提交：
&emsp; 本地代码库修改后需要使用git命令更新信息。首先使用status命令查看代码库修改状态，找到被修改对文件;然后用add命令依次添加修改后的文件;之后用commit命令添加修改说明;最后使用push命令完成对远程代码库更新
```sh
$ git status
$ git add README.md
$ git commit -m'add user guide'
$ git push
```
* ##### Windows:（Win7/Win10）
###### 待补充
* ##### Mac:
###### 待补充
