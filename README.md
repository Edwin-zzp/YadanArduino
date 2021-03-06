# YADAN ARDUINO

#### 介绍
这里是Yadan Arduino IDE开发板工具库

#### 安装教程

1.  在使用Arduino IDE进行Yadan程序开发时候首先需要安装Yadan board的相关配置文件以及工具。首先打开Arduino IDE，选择File->Preferences，在下图的框内填写Yadan board的配置文件的地址：https://raw.githubusercontent.com/Edwin-zzp/YadanArduino/main/package_verimake_core_index.json

![picture 1](images/ba928627bea65906102f654b868636244594bc10484ceae8fc49491c0f67d892.png)  

2.  完成后点击ok，然后选择Tools->Board->Board Manager…，在搜索栏中输入Yadan搜索，点击Install，安装完成后点击close。

3.  安装完成后在Tools->Board中就可以选择Yadan Core RISC-V（verimake）开发板。目前支持两个内核：Yadan 和 Zeroriscy。
![picture 2](images/8f0625fc1872da3f9240e474a01b3e5d028df5975cc75564eb43ca0fe9e72ba0.png)  


#### 使用说明

V1.0.0：
1.  目前支持Arduino的大部分函数，支持串口，定时器，spi。
2.  PWM对于所有IO都支持，频率为200Hz
3.  目前不支持AD和硬件IIC。

V1.0.1：

1、加入IIC支持，使用Wire类，需要手动安装库Wire.zip

2、Wire库下载地址：点击[Wire.zip](https://gitee.com/zhangzzp/yadan-arduino/raw/master/Libraries/Wire.zip)下载 。 使用方法在：https://verimake.com/topics/251


#### 即将支持
1、硬件IIC (已完成)

2、两路AD

