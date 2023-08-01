# Nginx

### 安装命令

```shell
root apt-get install nginx   	# 安装
service nginx start  			# 启动nginx
```

### 基本命令

```shell
nginx 				# 启动配置文件, 以默认配置文件
nginx -c 配置目录 	  # 指定配置文件启动
nginx -v   			# 查看安装版本
nginx -s reload 	# 执行重载命令
nginx -s stop 		# 关闭nginx
nginx -s quit 		# 完整有序的停止nginx，这个命令会等待所有请求结束后再关闭nginx
nginx -s reopen		# 重新打开日志文件
```



### 文件位置

```shell
/usr/sbin/nginx 	# 主程序
/etc/nginx			# 存放配置文件
/usr/share/nginx	# 存放静态文件
/var/log/nginx		# 存放日志
```



### 配置HTTPS

nginx -V ,  查看是否有"--with-http_ssl_module"

