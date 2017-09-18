#Golang

博客系统

采用Golang+beego

演示地址：

35.185.190.89

##编译安装说明：

设置GOPATH(安装目录)

	$ export GOPATH=/path/to/goblog
	$ cd /path/to/goblog

获取源代码，下载完成后会自动编译为goblog可执行文件
	
	$ go get github.com/cheongfa/goblog

修改数据库配置
	
	$ cd src
	$ vim github.com/cheongfa/goblog/conf/app.conf

导入MySQL

	......

运行
	
	$ ./goblog
	或
	$ nohup ./goblog 2>&1 > goblog.log &
	设为后台运行

访问： 

http://localhost:port

后台地址：

http://localhost:port/admin


