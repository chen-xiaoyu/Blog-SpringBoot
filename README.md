# SpringBoot
建立基于SpringBoot的博客过程记录  #注意版本号及其匹配问题
1. 基本环境配置：安装JAVA 1.8版本，配置gradle环境，下载eclipse EE。
Eclipse4JavaEE安装Gradle，并导入我们的Gradle项目https://www.cnblogs.com/SystemCall/p/10763866.html
2.基于eclipse配置springboot开发环境 https://www.cnblogs.com/yadiel-cc/p/11134225.html
3.显示HelloWorldSpringBoot开发环境搭建及配置 https://www.cnblogs.com/jedjia/p/spring_boot.html   
访问，这里什么都没写，默认 8080 ，默认根目录，所以访问就是  http://127.0.0.1:8080/hello 或者 http://localhost:8080 如果端口被占用，去kill该端口或去更改显示的端口。


# SpringBoot-HTML
1. 环境安装:maven+IntelliJ IDEA
在maven官方说明的命令中：mvn archetype:generate -DgroupId=com.nowcoder.mavendemo1  -DartifactId=mavendemo1 -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.4 -DinteractiveMode=false
创建文件夹，并在有pom.xml文件下的命令行，运行编译mvn compile，清除mvn clean，测试mvn clean test等程序
配置环境：
maven配置时选择 quickstart
注意maven在IDEA中版本匹配的问题
