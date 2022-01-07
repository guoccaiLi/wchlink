# WeAct-wchlink

## 简介
WCH-Link模块可用于沁恒RISC-V架构MCU在线调试和下载，也可用于带有SWD接口的ARM 内核MCU的在线调试和下载。同时带有1路串口，方便调试输出。 mini版本v1.0

### 特点
    - . Type-C 供电；
    - . 双电源输出：支持3.3V/5V；
    - . debug模式切换： 支持arm内核芯片、沁恒RISC-V；
    - . 支持SWD、带串口；
    - . 小巧易收纳；
    - . 通过按键切换模式，方便快捷；

###　模式切换
按住key键重新上电，指示灯跳变。后续使用中，wch-link 保持切换后模式。<br>
| 模式     |  指示灯  |  IDE |  支持芯片 |
|---|---|---|---|
|   |   |   |   |
|   |   |   |   |



## 外形图：
![外形图](Hdk/Wch-Link01.png)

##　尺寸图：
![尺寸图](Hdk/%E5%B0%BA%E5%AF%B8%E5%9B%BE.PNG)

## Using steps：
 1.Install the wchlink driver ---------Drv  <br>
 2.Read Doc--------------------------Doc   <br>
 3.Using wchlink by Tools -----------Tools  <br>

## important : 
it is a daplink for ARM,and it can be a RISV-V debugger for Qingheng risc-v mcu.