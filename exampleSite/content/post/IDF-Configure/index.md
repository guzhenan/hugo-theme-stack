+++

author = "G"

title = "ESP32-IDF环境配置"

date = "2024-06-07"

description = "ESP32-IDF配置教学"

tags = [

  "ESP32",

"ESP32开发环境"

]

categories = [

  "开发工具","嵌入式开发"

]

+++

### 官方使用指南文档链接

[ESP-IDF官方文档]([快速入门 - ESP32-S3 - — ESP-IDF 编程指南 release-v5.1 文档 (espressif.com)](https://docs.espressif.com/projects/esp-idf/zh_CN/release-v5.1/esp32s3/get-started/index.html))

## 前期准备

- 安装Git

- 安装VScode

- ESP32开发板

- Python环境

- Anaconda(可选)

## 配置ESP32-IDF环境

### 在VScode中的扩展里搜索“ESP-IDF”，之后点击下载

![](https://cdn.jsdelivr.net/gh/guzhenan/Picture/202406070030568.png)

### 下载完之后，点击进入安装开发环境的界面，选择快捷安装

![](https://cdn.jsdelivr.net/gh/guzhenan/Picture/202406070030553.png)

### 选择服务器、最新的版本、Git默认拉去所在的路径下，然后点击Install开始下载，大概需要等待20分钟左右的时间

![](https://cdn.jsdelivr.net/gh/guzhenan/Picture/202406070030570.png)

![](https://cdn.jsdelivr.net/gh/guzhenan/Picture/202406070030571.png)

### 进入下载页面，其会自动安装对应工具与环境，稍等片刻即可

![](https://cdn.jsdelivr.net/gh/guzhenan/Picture/202406070030569.png)

### 安装完成后，终端会显示如下界面，说明安装完成

![](https://cdn.jsdelivr.net/gh/guzhenan/Picture/202406070030567.png)

### 使用官方例程

弹出以下界面后，选择显示官方例子

![](https://cdn.jsdelivr.net/gh/guzhenan/Picture/202406070030566.png)

选择你当前的IDF版本

![](https://cdn.jsdelivr.net/gh/guzhenan/Picture/202406070030565.png)

创建案列工程

![](https://cdn.jsdelivr.net/gh/guzhenan/Picture/202406070030564.png)

选择工程路径

![](https://cdn.jsdelivr.net/gh/guzhenan/Picture/202406070030563.png)

### 插上开发板后选择对应，开发板的端口，在哪个端口可以通过设备管理里面的COM查看你对应的端口号

![](https://cdn.jsdelivr.net/gh/guzhenan/Picture/202406070030562.png)

### 选择对应的ESP32开发板类型，然后选择工程或者例程

![](https://cdn.jsdelivr.net/gh/guzhenan/Picture/202406070030561.png)

### 选择openocd的路径

![](https://cdn.jsdelivr.net/gh/guzhenan/Picture/202406070030559.png)

### 点击编译，第一次时间比较长，需要耐心等待大概1分钟左右

![](https://cdn.jsdelivr.net/gh/guzhenan/Picture/202406070030558.png)

显示如下界面代表着编译已经成功完成

![](https://cdn.jsdelivr.net/gh/guzhenan/Picture/202406070030557.png)

记得改下波特率 把他改成115200这样才不会终端才不会显示乱码

![](https://cdn.jsdelivr.net/gh/guzhenan/Picture/202406070030556.png)

![](https://cdn.jsdelivr.net/gh/guzhenan/Picture/202406070030555.png)

### 最后烧录程序到开发板

![出现如下界面代表烧录成功](https://cdn.jsdelivr.net/gh/guzhenan/Picture/202406072129202.png)

### 操作栏介绍

![](https://cdn.jsdelivr.net/gh/guzhenan/Picture/202406072125010.png)
