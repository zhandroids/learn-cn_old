## 简介
---
OCTOPUS PIR传感器模块是一种基于AM412热释电数字智能传感器的电子积木。它可用于感知和检测人体或动物的运动，感应距离约4-5米。 

 ![](https://i.imgur.com/j1VO7pH.jpg)

## 特性
---
- 具备octopus系列即插即用的特性。
## 技术规格
---
项目 | 参数 
:-: | :-: 
SKU|EF04055
电源|3.3V~5.5V
数字信号处理|SP
能耗|功率可调
输入|双向差分高阻抗传感器输入
抗干扰|内置滤波器，屏蔽其他频率的干扰
电源|出色的电源抑制，对RF干扰Schmidt REL输出不敏感
电压稳定性|低电压，低功耗，上电后瞬间稳定
工作温度|-25~85℃
尺寸|32.00mm×24.00mm


## 外形与定位尺寸
---

 ![](https://i.imgur.com/Ok6fmjF.jpg)

## 快速上手
---

### 所需器材及连接示意图
- 如图连接扩展板的P1口
***以sensor：bit为例***

![](https://i.imgur.com/5iwXCZp.png)
### 添加packege

### 如图所示编写程序

1.读取P1的红外信息

2.当信息为0显示一个心

3.当信息为1显示一个矩形

 ![](https://i.imgur.com/aMlPqo5.png)

### 参考程序

请参考程序连接：[https://makecode.microbit.org/_esoRoUPzUAhf](https://makecode.microbit.org/_esoRoUPzUAhf)

你也可以通过以下网页直接下载程序，下载完成后即可开始运行程序。

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_esoRoUPzUAhf" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>  
---

### 结果
- 当有物体接近，micro：bit上显示心形图案，当物体离开，micro：bit上显示矩形图案。

## 相关案例
---

## 技术文档
---
[datasheet](https://elecfreaks.com/estore/download/EF4055-Datasheet/https://www.elecfreaks.com/wiki/index.php?title=Octopus_PIR_sensor_Brick
)
