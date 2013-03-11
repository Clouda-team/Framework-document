## Sumeru MVC简介

在《Sumeru入门文档》中介绍了如何使用Suemru开发简单的“Hello World”，在“Hello World”中使用了Controller和View，Suemru采用MVC模式开发，在该文档通过“mvcTest”实例来介绍如何在Suemru框架中加入model。

### 一. Sumeru MVC介绍

首先简单的介绍一下Sumeru的MVC框架，Sumeru采用MVC（Model、View、Controller）模式开发，Model存放业务数据，View作为前端视图展现，在MVC模式下，View与Model是不能直接通讯，需要通过Controller将两者联系起来， Controller是Model与View的桥梁。

#### 1.1  Sumeru MVC模型图

Sumeru MVC模型图如下:

![](images/MVC_intro_1.1.png)

#### 1.2 Controller

Sumeru框架中Controller由onload()、onrender()、onready()三个⽣生命周期组 成,分别完成的功能如下:

##### 1.2.1 onload()






#### 1.3 View

















![](images/MVC_intro_2_2.1.png)



#### 2.2 具体实现方法

**(1) 在model文件夹下创建mvcTestModel.js和package.js文件**

mvcTestModel

	Model.mvcTestModel = function(exports){
	
		















package.js

	sumeru.packages{
	



	