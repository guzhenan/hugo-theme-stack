---

author = "G"

title = "微雪-ESP32-S-N8R8"

date = "2024-06-07"

description = "ESP32-IDF配置教学"

tags = [

"ESP32"

]

categories = [

  "开发板","嵌入式开发"

]

---

## 产品特性

- 采用 ESP32-S3-WROOM-1-N8R8模组，搭载 Xtensa 32 位 LX7 双核处理器，主频高达 240MHz
- 集成 512KB SRAM、384KB ROM、8MB PSRAM、8MB Flash 存储器
- 集成 2.4GHz Wi-Fi 和低功耗蓝牙 (Bluetooth LE) 双模无线通信，具有优越的射频性能
- 采用 USB Type-C 接口，无需纠结正反插
- 板载 CH343 与 CH334 芯片，通过一个 Type-C 接口就可以满足 USB 和 UART 开发使用需求
- 引出丰富的外设接口，引脚兼容 ESP32-S3-DevKitC-1 开发板，兼容性和扩展性强
- 邮票孔设计，可直接焊接集成到用户自主设计的底板上
- 支持多种低功耗工作状态，可调节通信距离、数据率和功耗之间的平衡，满足各种应用场景的功耗需求

## 支持的开发环境

- ESP-IDF
- Miropython
- Arduino

## 功能框架

![](https://cdn.jsdelivr.net/gh/guzhenan/Picture/202406080851798.png)

## 资源接口

![](https://cdn.jsdelivr.net/gh/guzhenan/Picture/202406080851796.png)

## 引脚分布

![](https://cdn.jsdelivr.net/gh/guzhenan/Picture/202406080851797.png)

## 产品尺寸

![](https://cdn.jsdelivr.net/gh/guzhenan/Picture/202406080851795.png)

## FAQ

**问题1**：模块上电后，识别出来的串口设备和USB口不断复位重启？

```tex
检查USB口的供电电压是否小于5V，一般情况下USB口的供电电压在4.9V以上，模块的两路USB口均可正常使用，若低于4.9V，则有可能出现供电不足，usb口掉线的情况，此种情况须更换足电压的USB口使用。
```

**问题**2：模块下载程序后，重新下载，有时会出现无法连接串口，或者烧录失败的情况？

```te
可长按BOOT按键，同时按下RESET，然后松开RESET，再松开BOOT按键，此时模块可进入下载模式，可解决大部分无法下载的问题。
```

  [CH343SER.7z](C:\Users\w\Documents\ZIP\CH343SER.7z) 

