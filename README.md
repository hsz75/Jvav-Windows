# Jvav Compile Platform 源代码

这只是一个梗, 并且当事人并不介意大家玩这个梗

如果您并不关心源代码,只想使用Jvav编译程序, 

请前往Jvav安装程序:[https://gitee.com/Doxfer/jvav_auxiliary/tree/master/]( https://gitee.com/Doxfer/jvav_auxiliary/tree/master/ )

## 源代码编译和运行

```shell
$ g++ Jvav.cpp JVMplus.cpp JVMplus.h
```

## 可执行文件使用方法

点击编译后的可执行文件, 

输入`compile {Jvav源文件名}.jvav`即可

目录下的`demo-cn.jvav`是一个关于Jvav语法的演示文档

```Jvav
JvavBegin

iNt mAiN(){  //iNt 为 整型变量
    cHaR ch = 'r';  //cHaR 为 字面量(字符)
    iNt n;         
    input n;         //使用input 变量/字符串/字符/重载了">>"运算符的类对象 进行程序输入
    output n magic 10;   //output 变量/字符串/字符/重载了"<<"运算符的类对象 进行程序输出,
    //并使用magic代替*(包括指针/解引用运算符和乘法的*都可以使用magic运算符)
    goBack ZERO;    //使用goBack 代替 return
    //并使用0-10的任意数字的英文单词大写代表0-10,如 ZERO ONE TWO等

    //除此之外,您可以使用if/else的大写字母IF/ELSE来进行条件控制
    //像使用while那样使用Loop,像使用for那样使用ConLoop
}

JvavEnd
```

