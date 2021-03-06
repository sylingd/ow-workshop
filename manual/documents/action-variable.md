---
title: 变量
lang: zh-CN
---

# 变量

## 设置全局变量    Set Global Variable

_将一个值存储为一个全局变量,全局变量即属于游戏本身的变量._

- `变量` 指定将值存储到哪个全局变量.
- `值` 此值将被存储.



## 设置玩家变量    Set Player Variable

_将一个值存储为一个玩家变量,玩家变量即属于一个特定玩家的变量._

- `玩家` 此玩家的变量将被设置.如果有多个玩家,则每个玩家的变量都被设置.
- `变量` 指定将值存储到哪个玩家变量.
- `值` 此值将被存储.



## 修改全局变量    Modify Global Variable

_修改一个全局变量的值,全局变量即属于游戏本身的变量._

- `变量` 要修改的全局变量.
- `操作` 变量的值改变的方式.选项包括标准运算操作,以及数组操作(如添加或移除值).
- `值` 用于修改的值.若要进行运算操作,则此值为两个运算量中的第二个,第一个运算量为变量当前的值.若要进行数组操作,则此值是用于添加或移除的值.



## 修改玩家变量    Modify Player Variable

_修改一个玩家变量的值,玩家变量即属于一个特定玩家的变量._

- `玩家` 此玩家的变量将被修改.如果有多个玩家,则每个玩家的变量都被设置.
- `变量` 要修改的玩家变量.
- `操作` 变量的值改变的方式.选项包括标准运算操作,以及数组操作(如添加或移除值).
- `值` 用于修改的值.若要进行运算操作,则此值为两个运算量中的第二个,第一个运算量为变量当前的值.若要进行数组操作,则此值是用于添加或移除的值.



## 对于全局变量    For Global Variable

_表示在循环中执行的一系列行动的开始, 并在每次循环时修改控制变量的值. 当前级别中的下一个end行动表示循环的结束. 如果执行至循环顶部时, 控制条件达到或超过终止值, 则退出循环, 跳至end操作之后的下一个操作执行._



## 对于玩家变量    For Player Variable

_表示在循环中执行的一系列行动的开始, 并在每次循环时修改控制变量的值. 当前级别中的下一个end行动表示循环的结束. 如果执行至循环顶部时, 控制条件达到或超过终止值, 则退出循环, 跳至end操作之后的下一个操作执行._



## 在索引处设置全局变量    Set Global Variable At Index

_为一个全局变量寻找或创建一个数组,然后将一个值储存至指定的索引处.全局变量即属于游戏本身的变量._

- `变量` 指定哪个全局变量的值是要修改的数组.如果变量的值不是一个数组,则使其值变为一个空的数组.
- `索引` 修改数组的索引.如果索引的位置已经超过了数组的末尾,则将数组延伸至索引位置,且新的元素值均为0.
- `值` 将此值存储到数组中.



## 在索引处设置玩家变量    Set Player Variable At Index

_为一个玩家变量寻找或创建一个数组,然后将一个值储存至指定的索引处.玩家变量即属于一个特定玩家的变量._

- `玩家` 此玩家的变量将被修改.如果有多个玩家,则每个玩家的变量都被修改.
- `变量` 指定哪个玩家变量的值是要修改的数组.如果变量的值不是一个数组,则使其值变为一个空的数组.
- `索引` 修改数组的索引.如果索引的位置已经超过了数组的末尾,则将数组延伸至索引位置,且新的元素值均为0.
- `值` 将此值存储到数组中.



## 在索引处修改全局变量    Modify Global Variable At Index

_修改索引处一个全局变量的值,全局变量即属于游戏本身的变量._

- `变量` 要修改的全局变量.
- `索引` 修改数组的索引.如果索引的位置已经超过了数组的末尾,则将数组延伸至索引位置,且新的元素值均为0.
- `操作` 变量的值改变的方式.选项包括标准运算操作,以及数组操作(如添加或移除值).
- `值` 用于修改的值.若要进行运算操作,则此值为两个运算量中的第二个,第一个运算量为变量当前的值.若要进行数组操作,则此值是用于添加或移除的值.



## 在索引处修改玩家变量    Modify Player Variable At Index

_修改索引处一个玩家变量的值,玩家变量即属于一个特定玩家的变量._

- `玩家` 此玩家的变量将被修改.如果有多个玩家,则每个玩家的变量都被设置.
- `变量` 要修改的玩家变量.
- `索引` 修改数组的索引.如果索引的位置已经超过了数组的末尾,则将数组延伸至索引位置,且新的元素值均为0.
- `操作` 变量的值改变的方式.选项包括标准运算操作,以及数组操作(如添加或移除值).
- `值` 用于修改的值.若要进行运算操作,则此值为两个运算量中的第二个,第一个运算量为变量当前的值.若要进行数组操作,则此值是用于添加或移除的值.



## 持续追踪全局变量    Chase Global Variable Over Time

_逐渐改变一个全局变量的值,全局变量即属于游戏本身的变量._

- `变量` 指定要改变的全局变量.
- `最终值` 该全局变量最后达到的值.这个值的类型可以是数字或矢量,然而必须与追踪开始时全局变量所具有的值相同.
- `持续时间` 变量到达最终值所用的时间,以秒为单位.
- `重新赋值` 指定此动作的某个输入值被持续重新赋值.此动作会要求输入新的数值,并用输入的数值进行重新赋值.



## 持续追踪玩家变量    Chase Player Variable Over Time

_逐步改变一个玩家变量的值,玩家变量即属于一个特定玩家的变量._

- `玩家` 此玩家的变量将被逐渐改变.如果有多个玩家,则每个玩家的变量都各自被改变
- `变量` 指定将要改变的玩家变量.
- `最终值` 该玩家变量最后达到的值.这个值的类型可以是数字或矢量,然而必须与追踪开始时玩家变量所具有的值相同.
- `持续时间` 变量到达最终值所用的时间,以秒为单位.
- `重新赋值` 指定此动作的某个输入值被持续重新赋值.此动作会要求输入新的数值,并用输入的数值进行重新赋值.



## 追踪全局变量频率    Chase Global Variable At Rate

_以指定的速率逐步改变一个全局变量的值,全局变量即属于游戏本身的变量._

- `变量` 指定要改变的全局变量.
- `最终值` 该全局变量最后达到的值.这个值的类型可以是数字或矢量,然而必须与追踪开始时全局变量所具有的值相同.
- `刷新率` 此变量的值每秒改变的量.
- `重新赋值` 指定此动作的某个输入值被持续重新赋值.此动作会要求输入新的数值,并用输入的数值进行重新赋值.



## 追踪玩家变量频率    Chase Player Variable At Rate

_以指定的速率逐步改变一个玩家变量的值,玩家变量即属于一个特定玩家的变量._

- `玩家` 此玩家的变量将被逐渐改变.如果有多个玩家,则每个玩家的变量都各自被改变.
- `变量` 指定将要改变的玩家变量.
- `最终值` 该玩家变量最后达到的值.这个值的类型可以是数字或矢量,然而必须与追踪开始时变量所具有的值相同.
- `刷新率` 此变量的值每秒改变的量.
- `重新赋值` 指定此动作的某个输入值被持续重新赋值.此动作会要求输入新的数值,并用输入的数值进行重新赋值.



## 停止追踪全局变量    Stop Chasing Global Variable

_停止追踪一个全局变量,并使其保持为当前值._

- `变量` 指定要停止修改的全局变量.



## 停止追踪玩家变量    Stop Chasing Player Variable

_停止追踪一个玩家变量,并使其保持为当前值._

- `玩家` 此玩家的变量将停止改变.如果有多个玩家,则每个玩家的变量都将停止改变.
- `变量` 指定要停止修改的玩家变量.
