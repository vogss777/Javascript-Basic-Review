# 变量与常量

### 1.变量

    + 用来存放数据，保存的数据可以进行修改
    + var、let 声明的就是变量，变量就是用来存储数据的容器。

### 2.常量

    + 用来存放数据，保存的数据不可修改（有特殊方法实现）
    + const 声明就是常量
    + const 声明常量的时候必须 赋初始值
    + const 声明的值类型是不允许重新赋值的
    + const 声明 引用类型，再不进行重新赋值的前提下，可以进行修改

### 3.变量与常量的本质

    + 无论是变量还是常量，其本身都是数据，也需要再内存中占用内存空间，保存再内存的栈结构区分中

### 4. let、const、var 的区别

    + let和const不允许<font color=red>重复声明</font>,var是可以重复声明的
    + let和const没有<font color=red>变量提升</font>,必须先声明后使用，var存在变量提升，可以先使用后声明
    + let和const有<font color=red>块级作用域</font>,var没有

### 5.基本（值）类型

    + Number
    + String
    + Boolean
    + null
    + undefinded
    + Symbol：唯一的数据
    + BigInt：任意精度的整数

### 6.堆栈概念，待补充

### 7.对象是什么

    + 对象（object）是键值对（k:v）的集合，表示属性和值得映射关系
    + 对象的创建方法：

    字面量的形式：

    ```js
        let obj = {
            name:'Tony',
            age：26
        };

    ----------------------------------------
    newObject()的形式：

    ```js
        let obj = new Object()
        obj.name = 'Aleen';
    ```
