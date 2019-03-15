 ![12](https://i.imgur.com/5RJ1KJn.jpg)  

## 简介
---
micro:bit上集成了丰富的传感器，其中就包含了加速度计。在这次的实验中，我们将利用micro:bit上的加速度计来做一个水平仪，并把倾角信号以柱状图形式显示在NeoPixel灯环上。 

## 元件清单
---
### 硬件：
- 1 x micro:bit
- 1 x USB线
- 1 x micro:bit面包板扩展板
- 1 x 面包板83 x 55 mm
- 1 x LED七彩灯环（8颗灯珠）
- 若干跳线

**温馨提示：如果你需要以上所有元件，你可以购买我们的[Elecfreaks小小科学家套件](https://item.taobao.com/item.htm?spm=a1z10.1-c-s.w4024-17803785896.2.18dc3f94XOgpWg&id=562837851877&scene=taobao_shop)。**

![](https://i.imgur.com/W4tseua.jpg)

## 主要元件介绍
---
### 加速度计

在你的micro:bit主板上有一个加速度计。它可以检测micro:bit的速度变化，将模拟信息转换成可以在micro:bit程序中使用的数字格式。输出的单位是毫克。这个装置也可以检测一小部分标准动作，例如：摇晃、倾斜以及自由落体。
 
![](https://i.imgur.com/kzqAOK4.jpg)

加速度计对应的X、Y、Z三个方向如下图所示：

![](https://i.imgur.com/FQ6zBkH.jpg) 

## 快速上手
---
### 硬件连接
根据下面的图片将你的元件连接起来：

- 将RGB灯的信号线与扩展板的P0口连接

![](https://i.imgur.com/NPvcrUo.jpg)

连接完成后如图:

![](https://i.imgur.com/SOD2TLb.jpg) 

### 软件

[微软Makecode在线编辑器:makecode.microbit.org](https://makecode.microbit.org/)

![](https://i.imgur.com/JHZUvh2.png)

### 添加Package
- 在MakeCode的代码抽屉中点击Advanced，查看更多代码选项。

![](https://i.imgur.com/smtcNoB.png)

点击“Extensions”，在弹出的对话框中搜索“neopixel"，下载neopixel代码库。

![](https://i.imgur.com/umQwUC2.png)

### 如图所示编写程序

![](https://i.imgur.com/bGPUFxy.png)

### 代码详解
- 将P0口设置为灯珠对应引脚，设置为RGB模式，将8颗灯珠全部点亮

![](https://i.imgur.com/NcVWUhr.png)

- 将灯珠点亮的颜色，设置为随加速度变化而变化的不同颜色

![](https://i.imgur.com/GBBTLVt.png)

### 参考程序
请参考程序连接：[https://makecode.microbit.org/_0Y07f36Y77sa](https://makecode.microbit.org/_0Y07f36Y77sa)

你也可以通过以下网页直接下载程序，下载完成后即可开始运行程序。

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_0Y07f36Y77sa" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>  
---

## 实验结果
---
随着micro:bit被移动，8颗RGB灯显示出不一样的颜色。

![](https://i.imgur.com/iq9Hxs0.gif)


## 思考
---
如果我们想控制4颗LED灯，让它们依次被点亮，那么我们该如何设计电路和编程呢？

## 常见问题
---

## 相关阅读
---
[Micro:bit小小科学家课程01:LED](/Micro_bit_Starter_Kit_Lesson_01_LED_CN/)                       
[Micro:bit小小科学家课程02:按钮](/Micro_bit_Starter_Kit_Lesson_02_Button_CN/)   
[Micro:bit小小科学家课程03:电位器](/Micro_bit_Starter_Kit_Lesson_03_Trimpot_CN/)   
[Micro:bit小小科学家课程04:光敏电阻](/Micro_bit_Starter_Kit_Lesson_04_Photocell_CN/)   
[Micro:bit小小科学家课程05:三色LED](/Micro_bit_Starter_Kit_Lesson_05_RGB_LED_CN/)   
[Micro:bit小小科学家课程06:自锁开关](/Micro_bit_Starter_Kit_Lesson_06_Self_lock_Switch_CN/)   
[Micro:bit小小科学家课程07:温度传感器](/Micro_bit_Starter_Kit_Lesson_07_Temperature_Sensor_CN/)   
[Micro:bit小小科学家课程08:舵机](/Micro_bit_Starter_Kit_Lesson_08_Servo_CN/)   
[Micro:bit小小科学家课程09:蜂鸣器](/Micro_bit_Starter_Kit_Lesson_09_Buzzer_CN/)   
[Micro:bit小小科学家课程10:电机](/Micro_bit_Starter_Kit_Lesson_10_Motor_CN/)   
[Micro:bit小小科学家课程11:七彩灯环](/Micro_bit_Starter_Kit_Lesson_11_Rainbow_LED_CN/)     
[Micro:bit小小科学家课程13:指南针](/Micro_bit_Starter_Kit_Lesson_13_Compass_CN/)     
[Micro:bit小小科学家课程14:环境光](/Micro_bit_Starter_Kit_Lesson_14_Ambient_Light_CN/)        

## 更多信息，欢迎访问：
---
[micro:bit知识库地址](https://www.elecfreaks.com/learn-cn/)    
micro:bit官方推荐供应商：[恩孚科技淘宝店](https://shop69086944.taobao.com/?spm=a230r.7195193.1997079397.2.RSthR0)  
QQ技术交流群：570756726   



