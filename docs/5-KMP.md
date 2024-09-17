# 西二在线 Android 第五轮考核：KMP

## 零、开始之前

* 注意，此KMP不是字符串匹配算法，全称为"Kotlin Multiplatform"，是JetBrains开发的一套跨平台开发框架。
* 由于该框架目前处于开发阶段，IOS端共享UI框架仍为Beta版本，Web端仍为Alpha版本，因此考核主要以Android和Desktop端为主。

## 一、知识点

* Compose 进一步学习
* Room 数据库
* 跨平台开发

## 二、参考教程

* [官方文档](https://www.jetbrains.com/kotlin-multiplatform/)
* [桌面应用教程](https://github.com/JetBrains/compose-multiplatform/tree/master/tutorials)
* [安装向导(你也可以在插件中找到它)](https://kmp.jetbrains.com/)


## 三、考核内容

实现一个简单的记账应用，要求如下： 
1. 允许新增、删除、修改、切换账本。
2. 账本首页显示账目名称、剩余金额、所有账单。
3. 允许新增、删除、修改账单。
4. 账单内容包括账目名称、金额、日期、备注。
5. 金额正为收入，负为支出。账单在账本首页按时间排序。

## 四、注意事项

* 软件UI设计可以参考市面上流行的任意一款记账应用。
* 请同时提供apk和msi/exe安装包。
* 对于想要进行IOS端开发的同学:
    1. 若没有条件，请先尝试使用虚拟机或双系统创造条件。
    2. 1. 若有Swift开发经验，请尝试原生UI的IOS开发。
       2. 若没有Swift开发经验，请尝试共享UI的IOS端开发。
    3. 若实现了IOS端的开发，请在PR文档中说明，并在项目中提供包含运行时截图的文件夹。
