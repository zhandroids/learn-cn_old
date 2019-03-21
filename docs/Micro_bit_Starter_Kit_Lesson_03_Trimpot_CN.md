 ![3](https://i.imgur.com/eN8vvty.jpg)

## 简介
---
电位器是一种普通的压力调节元件。在下面的实验中，我们将要读取电位器上的输出电压，并用柱形图的方式将它显示在micro:bit 5* 5 的LED屏幕上。 

## 元件清单
---
### 硬件：
- 1 x micro:bit  
- 1 x USB线  
- 1 x micro:bit面包板扩展板
- 1 x 面包板83 x 55 mm
- 1 x 10欧姆电位器  
- 若干跳线

**温馨提示：如果你需要以上所有元件，你可以购买我们的[Elecfreaks小小科学家套件](https://item.taobao.com/item.htm?spm=a1z10.1-c-s.w4024-17803785896.2.18dc3f94XOgpWg&id=562837851877&scene=taobao_shop)。**

![](https://i.imgur.com/W4tseua.jpg)

## 主要元件介绍
---
### 电位器
电位器是一种压力调节的元件。它包括了一个电阻和一个旋钮或者滑动系统。当添加一个外部的电压到电阻的两个固定接触点，通过使用旋钮或者滑动系统来改变电阻上的接触点的位置，一个和可移动的触点位置有特殊关系的电压就在可移动的触点和两个固定触点之间形成了。大部分时间，它就像一个分压器一样工作。 

![](https://i.imgur.com/uhr2hkg.jpg)

## 实验步骤
---
### 硬件连接
根据下面的图片将你的元件连接起来：

- 1.将电位器P0口与电位器s口连接
- 2.电位器的其他两个接口接GND与3V电源

![](https://i.imgur.com/ONL9HWv.jpg)

连接完成后如图:

![](https://i.imgur.com/dFGjHMH.jpg)

### 软件

[微软Makecode在线编辑器:makecode.microbit.org](https://makecode.microbit.org/)

![](https://i.imgur.com/JHZUvh2.png)

### 如图所示编写程序

![](https://i.imgur.com/PinA4U7.png)

### 代码详解
- 1.读取P0口返回的模拟信号(0~1023)，并以柱状图形式在点阵屏上显示。

![](https://i.imgur.com/PinA4U7.png)

### 参考程序
请参考程序连接：[https://makecode.microbit.org/_A2a4C65woMoc](https://makecode.microbit.org/_A2a4C65woMoc)

你也可以通过以下网页直接下载程序，下载完成后即可开始运行程序。

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_A2a4C65woMoc" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>  
---

## 实验结果
---
旋转定位器，电压的数值将会以柱形图的形式显示在micro:bit的5x5的LED屏幕上。当读取的电压为“0”，LED屏幕上只显示一个像素点。当电压变成3.3V的时候，LED屏幕将会被全部点亮。 

![](https://i.imgur.com/D5VDTS5.gif)

## 思考
---
如果我们想用电位器来调节LED灯的亮度，那么我们该如何设计电路和编程呢？

## 常见问题
--- 

## 更多信息，欢迎访问：
---
[micro:bit知识库地址](https://www.elecfreaks.com/learn-cn/)       
micro:bit官方推荐供应商：[恩孚科技淘宝店](https://shop69086944.taobao.com/?spm=a230r.7195193.1997079397.2.RSthR0)    
QQ技术交流群：570756726
