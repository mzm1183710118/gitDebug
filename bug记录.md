# bug记录

## 2021/8/7

### 问题：

![image-20210807180109301](C:\Users\HPDC0006\AppData\Roaming\Typora\typora-user-images\image-20210807180109301.png)

#### 解决：

进入.git文件夹，删除index.lock

![image-20210807180151266](C:\Users\HPDC0006\AppData\Roaming\Typora\typora-user-images\image-20210807180151266.png)

### 问题：

![image-20210807191230675](C:\Users\HPDC0006\AppData\Roaming\Typora\typora-user-images\image-20210807191230675.png)

### 解决：

进入本地仓库目录，使用下列指令：

```git
find . -name ".git" | xargs rm -Rf
```

即可成功删除.git文件夹。

