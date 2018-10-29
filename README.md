# PHP
WampServer - WampServer是一款由法国人开发的Apache Web服务器、PHP解释器以及MySQL数据库的整合软件包。
免去了开发人员将时间花费在繁琐的配置环境过程，从而腾出更多精力去做开发。
WampServer就是Windows Apache Mysql PHP集成安装环境，即在window下的apache、php和mysql的服务器软件。


PHP echo的语法如下：
void echo ( string $arg1 [, string $... ] )


类似于PHP echo语句，PHP print是一个语言结构(因为有返回值，可以认为它是函数)，
所以也不需要使用括号和参数列表。 
与echo不同，它总是返回1。
PHP print的语法如下：int print(string $arg)



$var(一个美元)是一个正常变量，名称为：var，存储任何值，如：string，integer，float等。
$$var(两个美元)是一个引用变量，用于存储$var的值。


PHP常量是在执行脚本期间无法更改的名称或标识符。 PHP常量可以通过两种方式定义：
使用 define() 函数定义
使用 const 关键字定义
PHP常量遵循相同的PHP变量规则。 例如，它可以只用字母或下划线开始。通常，PHP常量应以大写字母定义。


下面来看看看PHP中的define()函数的语法。define(name, value, case-insensitive)
name：指定常量名称。
value：指定常量值。
case-insensitive：默认值为false。默认情况下区分大小写。

const关键字在编译时定义常量。 它是一个语言构造不是一个函数。它比define()快一点，因为它没有返回值。