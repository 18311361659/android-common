# 安装JDK 1.7以上
# 安装gradle




### 打包

```
$ gradle aR
```

### 发布

```
$ gradle clean uploadArchives
```

### 使用
1.在repositories 添加

```
	mavenCentral()
   	//这里加入自己的maven地址
    maven {
        url "http://repo.bjcathay.com/content/groups/public/"
   	}
```
2.在dependencies 添加

```
	compile 'com.bjcathay:android:0.0.3'
```

# 模块

1. 基本工具
-----
- **Logger**：	一个Log工具类，不同的是这个Log具有一键开关功能，方便快速开发打开调试模式。
- **ValidationUtil**：	表单验证工具类，提供基本的验证方法，验证不通过会抛出运行时异常。
- **DialogUtil**：	吐司， 解决多次连续弹出提示问题，可只弹出最后一次，也可连续弹出轻量级提示。
- **StringUtil**：	字符串工具类


