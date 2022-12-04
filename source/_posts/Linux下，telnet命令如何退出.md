# Linux下，telnet命令如何退出

测试连接本地一个服务端口

```shell
 telnet 127.0.0.1 11211
```

链接后是这样的：

```shell
wangkongming@Vostro ~ $ telnet 127.0.0.1 11211
Trying 127.0.0.1...
Connected to 127.0.0.1.
Escape character is '^]'.
```

 

如何退出呢？　

ctrl+],然后再按q就可以退出