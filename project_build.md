# 项目构建 #

将项目从svn checkout下来,源代码在[source](source.md)，安装maven并进行根目录运行命令:
```
mvn install -Dmaven.test.skip=true
```

-Dmaven.test.skip=true意思是不运行单元测试. 构建出来的产品在你的本地mvn仓库. mvn groupId是com.googlecode.rapid-framework