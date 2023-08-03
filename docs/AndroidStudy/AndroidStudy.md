# Android 入门

## 目录解析

![Android项目常规目录](./img/project_directory.png)

- <u>*FuuComposePlugin*</u>

  这是初始创建的项目，该项目包括两个app项目（app/news_lib），以及构建工具gradle。真正我们写的app是在app这种模块中的代码打包出来的，而app/news_lib模块以外的都是用于构建app



- <u>*gradle*</u>

  gradle的配置，在这里面可以设置gradle的版本，和其他配置



- <u>*settings.build.kts*</u>

  配置整个项目的的gradle插件配置等



- <u>*app/news_lib(我自己创建的模块)*</u>

  这是两个是独立的apk应用

  ![app目录](./img/app_directory.png)

以app模块为例,

- <u>*app\src\build.gradle.kts*</u>  是用 构建该模块的脚本文件
- <u>*app\src\main*</u>  工作区
- <u>*app\src\test*</u>  测试区
- <u>*app\src\main\java*</u>  源代码位置，也就是我们写代码的主要工作区
- <u>*app\src\main\res*</u>  资源存区，用于存放xml/jpg等各种资源文件
- <u>*app\src\main\AndroidManifest.xml*</u>  android注册表，在这里，你需要为activity，手机权限等进行注册

