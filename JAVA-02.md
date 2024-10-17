#Task1

##（1）

###代码结构

package com.ISEKAI;
包声明：这是说明文件所在的包
import com.ISEKAI.tool.Print;
导入print工具类
public class HelloWorld {
        public static void main(String[] args){
            Test.test();
        }
}
说明了Helloworld公共类，作为程序的入口点

main方法，作为程序的入口

class Test{
    public static void test(){
        Print.print("Hello World");
    }
}

引入tast类，其中有test方法用来打印目标字符串

###package

它可以把一些相似的类放在一个包中，相当于一个管理类的文件夹。它可以方便类的查找和使用，同时对于类，使用时可以加上包名加以区分，这就避免了名字冲突。

###main函数

它是java程序的入口方法，它是程序执行时第一个被执行的方法

###单文件java程序的基本结构

包声明，即package(可选)

导入语句，即import

类，java程序总是从一个或多个类开始

主方法（main）：它是程序执行的起点因此所有java程序都有

##（2）

