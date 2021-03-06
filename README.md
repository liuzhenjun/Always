# Yeoman的使用

=============================
    该文件是用来介绍yeoman工具，他的目标是通过grunt或gulp和bower等各种工具来为开发者创建一个易用的工作流。
    而且Yeoman的目的不仅是要为新项目建立工作流，同时还是为了解决前端开发面临的零散的依赖关系。

****
###                    Author：zhenjun
###              E-mail：1182799153@qq.com

=============================

##目录
* [Yemoman介绍](#介绍)
* [Yemoman安装步骤](#安装步骤)
* [Yemoman前景](#前景)
* [Yemoman开发实例](#开发实例)
     * [Yeoman搭建一个gulp+sass+bootstrap的pc端项目](#Yeoman-bootstrap)
     * [Yeoman搭建一个Angular+gulp+AngularJS的pc端项目](#Yeoman-AngularJS)
* [Yemoman相关工具](#工具)
* [Yemoman开源地址](#开源地址)

========================
  
介绍
--------------
    Yeoman帮助我们创建项目，提供更好的工具来使我们的项目更多样化。
    Yeoman提供generator系统，一个generator是一个插件，在我们在一个完整的项目上使用‘yo’命令时，会运行该generator。通过这些官方的Generators，推出了Yeoman工作流，工作流是一个健壮、有自己特色的客户端堆栈，包含能快速构建漂亮的网络应用的工具和框架。Yeoman提供了负责开始项目开发的一切，没有任何让人头痛的手动配置。

    采用模块化结构，Yeoman利用从几个开源社区网站学习到的成功和教训，以确保栈开发人员越来越智能的进行开发。基于良好的文档基础以及深思熟虑的项目构建过程，Yeoman提供测试和其他更多技术 ，因此开发人员可以更专注于解决方案而不用去担心其他小事。

    Yeoman主要提供了三个工具：脚手架（yo），构建工具（grunt），包管理器（bower）。这三个工具是分别独立开发的，但是需要配合使用，来实现我们更高效的工作流模式。
　　
==========================
　　
安装步骤
---------------
        1.安装Node.js
        2.安装git
        3.安装Yeoman
            npm install -g yo grunt-cli bower
        4.安装generator
        在终端命令行中输入yo命令，然后用上下键控制选择install a generator，然后选择webapp
        也可以直接在命令行中输入 mpm install -global generator-webapp(以webapp为例)
  
=============================

前景
---------------

============================

开发实例
Yeoman-bootstrap
代码所在地址：https://github.com/liuzhenjun/yeoman-bootstrap
---------------

     ##Yeoman搭建一个gulp+sass+bootstrap的pc端项目
     1.创建一个工作目录，用于存放bootstrap项目，并从终端进入
     2.在终端分别安装工具和项目发生器，命令分别为:npm install -global yo,npm install -global generator-webapp
     3.在终端输入yo webapp，进行项目的创建，然后通过上下键控制选择bootstrap
     4.在生成的项目文件里，我们进入app文件，在本文件下，我们进行项目的开发
     5.在终端使用gulp server 命令打开浏览器进行预览，yeoman已经自动帮我们创建好了gulp工具，server服务器启动后会自动对我们的app里的代码进行监听，如果我们修改代码，浏览器会自动刷新。
     6.项目开发完成后，我们在终端使用gulp build命令对项目进行构建，此时，在工作目录下会自动生成dist文件夹，dist文件夹里的项目就是我们最终需要提交的项目。
    
Yeoman-AngularJS
代码所在地址：
---------------

     ##Yeoman搭建一个Yeoman+AngularJS+gulp的web应用
     1.创建一个工作目录，用于存放Angular项目，并从终端进入
     2.在终端分别安装工具和项目发生器，命令分别为:npm install -global yo bower grunt-cli gulp, npm install -global generator-angular
     3.
     4.
     5.
     6.

============================


工具
---------------

==============================

开源地址
----------------
