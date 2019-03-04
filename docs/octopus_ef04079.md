## 简介
---
Octopus TMP36温度传感器模块是一种温度传感器，具有低电压和精确的摄氏读数。 它可以提供电压输出，与摄氏温度形成线性关系

 ![](https://i.imgur.com/zqYYROQ.jpg)

## 特性
---

- 具备octopus系列即插即用的特性。

## 技术规格
---
项目 | 参数 
:-: | :-: 
SKU|EF04079
精度|±2°C（整个温度范围内的典型值）
线性度|±0.5°C（典型值）
低工作电压|2.7V~5.5V
热效应指标|当电源货币低于50μA时
指定温度测量范围|-40°C至+ 125°C，工作温度可高达+ 150°C
比率系数|+ 10 mV /°C
静态电流|低于50μA
关闭电流|最大0.5μA

## 外形与定位尺寸
---

 ![](https://i.imgur.com/e5NlyhB.png)

## 快速上手
---

### 所需器材及连接示意图
- 如下图所示连接扩展板的P1口

***以sensor:bit为例***

 ![](https://i.imgur.com/bLgrtiX.png)

### 添加packege
在MakeCode的代码抽屉中点击Advanced，查看更多代码选项。

 ![](https://i.imgur.com/smtcNoB.png)

点击“Extensions”，在弹出的对话框中搜索“iot"，下载iot代码库。

 ![](https://i.imgur.com/dsPDNvD.png)

### 如图所示编写程序
1.调用micro：bit的led显示模块

2.调用iot函数库中的读取温度的函数

3.显示相关的温度

 ![](https://i.imgur.com/PvPxhtr.png)

### 参考程序
---
请参考程序连接：[https://makecode.microbit.org/_URRdVrPFX68R](https://makecode.microbit.org/_URRdVrPFX68R)

你也可以通过以下网页直接下载程序，下载完成后即可开始运行程序。

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_URRdVrPFX68R" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>  
---

### 结果
- micro:bit led显示器上显示出当前环境的温度值。

## 相关案例
--

## 技术文档
--
