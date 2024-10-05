### TASK1

#### JDK

JDK是java的开发工具包，为程序员提供了编写，编译，调试Java程序所需要的工具，还包含了JRE以及基础类库。

#### JRE

JRE 为Java程序提供了一个运行环境，使得Java程序可以再不同的操作系统上运行。

#### JVM

JVM是Java虚拟机，在计算机上仿真模拟各种计算机功能来实现Java程序的跨操作系统运行，是执行Java程序的核心组件。

#### 关系

1.JVM是JRE的核心组件，没有JVM,JRE无法执行Java程序

2.JDK包含了JRE，JRE包含了JVM

3.JDK用于开发，JRE用于运行，JVM为Java程序提供了一个平台去运行



### TASK2

我配置的环境变量

新建了一个变量名叫JAVA_HOME

值为C:\Program Files\Java\jdk-1.8

再在Path中添加%JAVA_HOME%\bin



因为如果执行的程序在当前目录下不存在，Windows就会在一个叫做path的环境变量指定的目录中查找。配置环境变量就能保证无论在哪里打开终端都能执行javac，java 这两条指令



### TASK3

1. .java文件是保存java代码的文件
2.  使用javac命令对java文件进行编译后就会生成.class文件，最终运行的时候是运行.class文件。

