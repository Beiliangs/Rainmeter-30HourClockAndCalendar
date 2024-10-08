# Rainmeter-30HourClockAndCalendar
A Rainmeter Skinpack which can support 30 hour clock and calendar
### 简介
- 如你所见，这是一个Rainmeter皮肤包，让你可以使用30小时制的桌面时钟
- 如果你不知道什么是30小时制，请前往[这里](https://zh.moegirl.org.cn/30小时制)了解;
- 如果你不知道什么是Rainmeter，请前往[这里](https://docs.rainmeter.net/manual/getting-started/)了解

### 使用方法
1. 如果你没有安装Rainmeter，请前往[这里](https://www.rainmeter.net/)下载安装;
2. 下载[release](https://github.com/Beiliangs/Rainmeter-30HourClockAndCalendar/releases)里的.rmskin文件，用Rainmeter打开，按照Rainmeter的要求安装皮肤包

### 说明
- 因为本人技术有限，无法做到根据屏幕分辨率自动调整大小。所以如果出现与屏幕大小不匹配的情况，请自行修改源码中的Width与Height参数;
- 同样地，修改参数之后如果出现文字不齐的情况，请自行调整;
- 请自行修改显示字体
- 参数修改参考以下代码:
```
[Variables]
; General Section #2

Width=*这里写组件宽度(单位:像素)*
Height=*这里写组件高度(单位:像素)*
UpdateFreq=*这里写刷新周期(单位:毫秒)*

BackgroundColor=*这里写组件背景颜色(格式:R,G,B,A)*
BorderColor=*这里写组件文字描边颜色(格式:R,G,B,A)*
TextColor=*这里写组件文字颜色(格式:R,G,B,A)*

Font=*这里写字体名字(字体要安装在系统里)*
```
- 默认参数如下:
```
[Variables]
; General Section #2

Width=380
Height=80
UpdateFreq=1

BackgroundColor=0,0,0,32
BorderColor=0,0,0,255
TextColor=255,255,255,255

Font=Rounded-X M+ 1c regular
```
<p xmlns:cc="http://creativecommons.org/ns#" >This work is licensed under <a href="https://creativecommons.org/licenses/by-nc/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1" alt=""></a></p>
