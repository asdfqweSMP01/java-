# java-
Java课程实验
实验二模拟机程序
＃实验内容
用类描述计算机中CPU的速度和硬盘的容量，要求Java应用程序有4个类，名字分别为：pc CPU硬盘和Test，其中TEST是主类。
##实验目的
（1）使用多种方法分别描述硬盘，cpu，pc的属性
（2）完成类型，属性和修饰长度
##实验过程
(1)CPU 类 getSpeed()返回 speed 的值， setSpeed(int m)方法将参数 m 的值 赋值给 speed。同样将n赋值	给frequency	
（2）HardDisk类getAmount（）返回amount的值，setAmount（int m）方法将参数m的值赋值给定value，getSpeed（）返回speed的值，setSpeed（int m）方法将参数n的值赋值给定speed
（3）PC类setCPU（CPU c）将参数c的值赋值给cpu，setHardDisk（HardDisk h）方法将参数h的值赋值给HD，show（）方法能显示cpu的速度和频率以及硬盘的容量和这类。
（4）通过以上编写主类
##核心方法
（1） main 方法中建立一个 CPU 对象 cpu，cpu 将本身的 speed 设置为 2200； blog
（2） main 方法中建立一个 HardDisk 对象 disk，disk 将本身的 amount 设置为 200； get
（3） main 方法中建立一个 PC 对象 pc； class
（4） pc 调用 setCPU(CPU c)方法，调用时实参是 cpu； 程序
（5） pc 调用 setHardDisk(HardDisk h)方法，调用时实参是 disk; 方法
（6）pc调用show（）方法。
##实验结果
中央处理器速度为2200，频率为10
硬盘容量为200，预设为5000
##实验感想
并且了解到类是Java中最基本的组成单元，Java将描述一类对象的属性（状态）和功能（行为）封装在一起，属性用成员变量来刻画；功能通过方法来实现以及关于构造方法如果没有明显式地为类定义构造方法，Java编译器将会为该类提供一个替代构造方法。在创建一个对象的时候，至少要调用一个构造方法。构造方法的名称必须与类同名，一个类可以有多个构造方
法，也使我了解到了多种方法的使用。但在实验中还有很多不足，在将来的实验中能够继续改进和完善
