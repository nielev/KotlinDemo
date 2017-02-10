# KotlinDemo
##Kotlin简介
Kotlin 是一个基于 JVM 的新的编程语言，由 JetBrains 开发。
其主要设计目标：
创建一种兼容 Java 的语言
让它比 Java 更安全，能够静态检测常见的陷阱。如：引用空指针
让它比 Java 更简洁，通过支持 variable type inference，higher-order functions (closures)，extension functions，mixins and first-class delegation 等实现。
让它比最成熟的竞争对手 Scala 语言更加简单。
##kotlin使用文档
http://kotlindoc.com/index.html
##Kotlin的基本环境配置
module的build.gradle配置
![build1](https://github.com/nielev/KotlinDemo/blob/master/app/src/main/res/mipmap-hdpi/build1.png)

root build.gradle配置
![build1](https://github.com/nielev/KotlinDemo/blob/master/app/src/main/res/mipmap-hdpi/build2.png)

配置完gradle，还需要安装kotlin和kotlin Extensions插件，才能正常使用将java转换kotlin功能
![build1](https://github.com/nielev/KotlinDemo/blob/master/app/src/main/res/mipmap-hdpi/setting.png)

最后，选中activity，在Code标题栏下，选中Covert Java File To Kotlin File.大功告成
