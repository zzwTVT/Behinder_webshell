```
编译打包都是用的：
java version "1.8.0_202"
Java(TM) SE Runtime Environment (build 1.8.0_202-b08)
Java HotSpot(TM) 64-Bit Server VM (build 25.202-b08, mixed mode)
建议java8运行
```



# 冰蝎V4.1目前最新版二开

1.  修改了3个强特征指纹。
2.  新加了6个流量加密算法，过流量检测就用这个6个算法的就行。（DIY的是java、php、aps、apsx文件都有，我只验证了java和php的一定能用）
3.  流量算法协议可自定义，比哥斯拉好解耦。

```
tip:
传输协议配置中的本地验证只能验证java语言的，其他语言都得找对应环境验证（webshell）
原来冰蝎自带的流量传输协议也还能用，就是可能会被设备检测到流量特征，指纹特征是都抹去了
```

