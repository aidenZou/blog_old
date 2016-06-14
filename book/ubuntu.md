## Nginx

### **install**

```
apt-get update
apt-get install nginx
```

### 配置文件位置

`/etc/nginx/nginx.conf`
这个配置文件会包含 `/etc/nginx/conf.d/*.conf`
默认主目录：`/usr/share/nginx/html/`

### 管理 nginx服务

```
$ service nginx start # 启动
$ service nginx stop # 停止
$ service nginx restart # 重启
```


