# 适合中国Java程序员编译的环境说明

### 环境准备

> 如果是Windows平台，这个版本的ES需要JDK起步为JDK11，我们平时开发都是使用的JDK8，
> 如果是JAVA_HOME配置的是11就当我说的是废话哈！

> 在不影响原来环境的同时，ES是支持JAVA11_HOME环境变量的，所以可以设置JDK11变量为JAVA11_HOME=您的JDK11路径

### 每次Gradle都得下载，烦人啊，国内下载还很慢，怎么办？

> 修改 当前项目路径下 gradle/wrapper/gradle-wrapper.properties
> 的distributionUrl=file:///【你自己路径的Gradle，推荐使用6.1.1】
> 举个栗子：distributionUrl=file:///d:/InstallSoft/gradle-6.6.1/gradle-6.6.1-all.zip
