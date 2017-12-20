# RStudio

## RStudio服务器重启失败

```
initctl: Unknown instance
```

查看使用8787端口的进程：

```
sudo fuser 8787/tcp
```

关闭所有使用8787端口的进程：

```
sudo fuser -k 8787/tcp
```

重启RStudio服务器：

```
sudo rstudio-server start
```



