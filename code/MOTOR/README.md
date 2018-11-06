Motor A和Motor D连接电机：两个电机同时以25%占空比正转或者反转

## BPI:bit BPI:bit robot expansion board Servo Control Demo!

 ![bpi:bit](https://forum.banana-pi.org.cn/uploads/default/original/2X/e/e5557db2dec86b6bf402c5eb4d35b5c1bb668f0e.JPG)

> ### 开发平台：
> VS Code1.21.0

> PlatformIO 3.5.3a7

----
> 验证：串口：9600-1-8-N
----
> `/src/main.cpp`为测试程序主体代码，

#### 使用方法：
- 编译：
终端内执行`platformio run`

- 烧录:
终端内执行`platformio run --target upload`

（需要提前预装`Atom/VSCode`软件，安装`PlatformIO`扩展，并且在`PlatformIO`里面下载`ESP32`平台）本段代码可以用于`Arduino`编译，但需要安装平台支持与库扩展等等。[安装教程](/programing/Arduino_IDE)

#### 主要测试功能介绍：

- 通过BPI:bit robot expansion board控制两组直流电机Motor A和Motor D连接电机：两个电机同时以25%占空比正转或者反转

#### 支持库安装
- 首先需要安装库：[PCA9685 PWM Servo Driver Library](https://github.com/adafruit/Adafruit-PWM-Servo-Driver-Library)
- 库安装方法：在Platform IO的扩展库管理器面搜索
