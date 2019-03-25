## 简介
---
- Ring:bit car V2灯条模块，是Ring:bit二代小车的专用扩展模块，连接简单功能强大，一卡一锁为你的Ring:bit小车扩展更多灯带。
- 搭载8颗Rainbow LED灯珠，全彩色，可以实现自动车灯、彩虹车灯等功能。
 
 ![](https://i.imgur.com/keVKcZt.jpg) ![](https://i.imgur.com/1MpxeNl.jpg)

## 特性
---
- 输入电压为3V~5V，micro:bit能直接驱动。

- 标准的3线GVS接口，仅占用一个IO口。

- 8颗小型灯珠，更加省电。

- 每颗灯珠都可以独立编程，显示RGB色彩。

## 参数
---

 项目 | 参数 | 备注
 :-: | :-: |:-:
 品名|Ring:bit car v2专用灯条扩展模块|-
 SKU|EF03425|-
 工作电压|DC 3-5V|-
 接口|Ring:bit car专用弹针卡口|螺丝固定
 输出信号类型|模拟|-
 搭载灯珠|8颗|-
 尺寸|60.8 x 33.20mm|-
 净重|5.7g|-


## 外形与安装定位尺寸
---

 ![](https://i.imgur.com/oMYvA7j.png)

## 快速上手
---	
### 硬件连接  
---

- 首先将灯条模块插入Ring:bit小车底板插口。
 
 ![](https://i.imgur.com/W74Qmw5.gif)

- 随后在反面用两颗螺丝固定。

 ![](https://i.imgur.com/DdDtrst.gif) ![](https://i.imgur.com/rmNWX7j.gif)

- 扩展完成。

 ![](https://i.imgur.com/SkGJN5h.jpg)

- 要使用Ring:bit小车的Rainbow功能，请在基础板上将开关拨动至Rainbow LED功能。

 ![](https://i.imgur.com/CfGTC9t.jpg)

### 软件编程  
---

- 在[makecode](https://makecode.microbit.org/)在线编辑器中编写一段简单的彩虹灯代码。

 ![](https://i.imgur.com/zqBmuEN.png)

- 从Neopixel积木块中拖出`NeoPixel at pin……`积木块，插入到`On Start`积木块中。
- 将10颗连接到P2口的Rainbow LED存储到`all_led`变量中。

 ![](https://i.imgur.com/P8dTKHu.png)

- 在`forever`积木块中设置`Single`变量为所有LED`all_led`中从`choice`颗开始的第一颗灯。
- `choice`变量依次加一，依次选择10颗灯。

 ![](https://i.imgur.com/vU8l2P2.png)

- 当选择变量`choice`大于9时，意味着选择到最后一颗灯，将`choice`变量设置为0，重新循环。

 ![](https://i.imgur.com/2jda8fX.png)

- 将选择好的灯`single`显示`red`红色，延迟200ms后，熄灭LED。

 ![](https://i.imgur.com/qbAvPFJ.png)

 程序代码链接：[https://makecode.microbit.org/_cg0JCtE5HHET](https://makecode.microbit.org/_cg0JCtE5HHET)

 你也能通过下列窗口直接下载代码：

 <div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_cg0JCtE5HHET" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

### 结果
---
- 顺序点亮Rainbow LED。

 ![](https://i.imgur.com/RuCcyiq.gif)

## 文档
---
[WIKI](https://github.com/elecfreaks/learn-cn)

## 常见问题
---
