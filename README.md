## 整体流程交互
本demo主要是用于演示数据交互过程，性能很一般，仅供各选手参考
![enter image description here](https://tianchi-public.oss-cn-hangzhou.aliyuncs.com/public/files/forum/158937741003137571589377409737.png)


## 测评程序
```
java -Dserver.port=8080 -DcheckSumPath=/software/workspace/aliyun/demo/trace/checkSum.data -jar /software/workspace/aliyun/demo/scoring-1.0-SNAPSHOT.jar
```

```
java -Dserver.port=8080 -DcheckSumPath=/software/workspace/aliyun/demo/checkSum.big/checkSum.data -jar /software/workspace/aliyun/demo/scoring-1.0-SNAPSHOT.jar

```