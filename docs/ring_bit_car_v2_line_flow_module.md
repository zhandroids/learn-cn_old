## 简介
---
- Ring:bit car V2巡线模块，是Ring:bit二代小车的专用扩展模块，连接简单功能强大，一卡一锁为你的Ring:bit小车扩展巡线功能。
- 搭载双红外探头，有效探测距离2~12mm，可以完成巡线绕圈，黑线检测，边缘检测等功能。
 
 ![](https://i.imgur.com/IZEjlSs.jpg) ![](https://i.imgur.com/x5TV42w.jpg)

## 特性
---
- 输入电压为3V~5V，micro:bit能直接驱动。

- 标准的3线GVS接口，仅占用一个IO口。

- 利用红外光探测，抗干扰能力强

## 参数
---

 项目 | 参数 | 备注
 :-: | :-: |:-:
 品名|Ring:bit car v2专用巡线扩展模块|-
 SKU|EF03424|-
 工作电压|DC 3-5V|-
 接口|Ring:bit car专用弹针卡口|螺丝固定
 输出信号类型|模拟|-
 有效距离|2~12mm|-
 尺寸|34.15 x 27.20mm|-
 净重|4.7g|-


## 外形与安装定位尺寸
---

 ![](https://i.imgur.com/R1Xee8w.png)


## 快速上手
---	
### 硬件连接  
---

- 首先将巡线模块插入Ring:bit小车底板插口。
 
 ![](https://i.imgur.com/LOXjMgx.gif)

- 随后在反面用两颗螺丝固定。

 ![](https://i.imgur.com/rM1zdpz.gif) ![](https://i.imgur.com/T5ptc8F.gif)

- 扩展完成。

 ![](https://i.imgur.com/BcVzgia.jpg)

- 要使用Ring:bit小车除了Rainbow LED外的其他功能，均要将底板的拨片开关拨到`other modules`一侧。

 ![](https://i.imgur.com/jrWzkFJ.jpg)

### 软件编程  
---

- 在[makecode](https://makecode.microbit.org/)在线编辑器中编写一段简单的巡线代码。

 ![](https://i.imgur.com/qxE2Vto.png)

- 开机时初始化左右轮连接口为P1和P2。
- 然后以100的速度前进。

 ![](https://i.imgur.com/52DzbGf.png)

- 当左检测头偏离黑线，右轮停止，左轮以50的速度以矫正回归黑线。

 ![](https://i.imgur.com/5J1Vx9h.png)

- 右检测头同理。

 ![](https://i.imgur.com/SVUxLr8.png)

- 当两个检测头均检测到黑线，以100的速度向前行驶。

 ![](https://i.imgur.com/CcO2RN6.png)

 程序代码链接：[https://makecode.microbit.org/_Jh2RVDMRwDz1](https://makecode.microbit.org/_Jh2RVDMRwDz1)

 你也能通过下列窗口直接下载代码：

 <div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_Jh2RVDMRwDz1" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

### 结果
---
- 可以实现缓慢的巡线绕圈跑。

 ![](https://i.imgur.com/B3YyUIc.gif)

## 文档
---
[WIKI](https://github.com/elecfreaks/learn-cn)

## 常见问题
---
