# Zhangqing
计181  张青  2018310756



一、实验目的

  分析学生选课系统
  使用GUI窗体及其组件设计窗体界面
  完成学生选课过程业务逻辑编程
  基于文件保存并读取数据
  处理异常
  
  
二、实验要求

1、设计GUI窗体，支持学生注册、课程新加、学生选课、学生退课、打印学生选课列表等操作。

2、基于事件模型对业务逻辑编程，实现在界面上支持上述操作。

3、针对操作过程中可能会出现的各种异常，做异常处理

三、实验过程

1、编写思路

    先画出流程图，确定需要实现哪些功能，然后再根据框架写出程序。先确定需要哪些包（swing\awt\IO），将包导入，导入后先构建整体的GUI的所有界面，         
将界面通过监听事件相连接。然后在需要文本写入与文本读出的地方的界面写上文本操作。而打印课表则是通过将文件打开，显示出学生基本信息、所选课程来实现
的。

2、流程图

![hahaha](https://github.com/DuXuchen/Zhangqing/blob/master/流程图.png)


3、核心代码

GUI部分

![hahah](https://github.com/DuXuchen/Zhangqing/blob/master/GUI界面.png)

录入学生信息

![hhh](https://github.com/DuXuchen/Zhangqing/blob/master/录入学生信息.png)


录入课表：

![](https://github.com/DuXuchen/Zhangqing/blob/master/录入课表.png)


打开文件：

![lll](https://github.com/DuXuchen/Zhangqing/blob/master/打开文件.png)


四、运行结果：

用户选择

![](https://github.com/DuXuchen/Zhangqing/blob/master/用户选择.png)


注册界面：

![](https://github.com/DuXuchen/Zhangqing/blob/master/注册.png)


学生选课操作

![](https://github.com/DuXuchen/Zhangqing/blob/master/学生选课.png)

课表输出：

![](https://github.com/DuXuchen/Zhangqing/blob/master/输出课表.png)


教师页面

![](https://github.com/DuXuchen/Zhangqing/blob/master/教师页面.png)


五、实验总结及感想：
    最后一个实验，不知不觉间，Java的课程就此结束，但是对于我的学习，其实很不满意，首先就是自己的态度没端正，和开学时候的预想截然不同，值得反思。
 虽然学的不好，但是总的来说对它有了一些基础的了解，基础的操作还是能掌握，身为计算机的我们，对开发语言必须会，而Java的学习，虽没学好，但是也为自
 己课下学习提供了一部分基础。
    其次就是这次实验，通过了那么多次实验，这次试验和上几次的都有联系，功能差不多，但是所用知识确是最多的，我无法独立完成，在同学的帮助下，查找资
 料等，才得以完成.同学之间的互相帮助让我特别的感动。课程截至了，但是学习是终生的，学习仍在继续。  
