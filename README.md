## 环境依赖

+ Keil v5.31

+ STM32cubeMX6.1.0

## 主控芯片

STM32F103 C8T6


## 目录结构描述

* [Core]()
* [doc]()
  * [databook]()
  * [schematic]()
* [Drivers]()
* [MDK-ARM]()
* [.gitignore]()
* [readme]()


## 功能概述

- TIM2发送1k hz的占空比90%的pwm控制步进电机转动,以10s为一个周期滑块前后移动。

## IO口对应说明

PA1     ------> TIM2_CH2

PA5     ------> PUL_PIN

PA6     ------> DIR_PIN​

## 接线图示
采用的是共阴极接法
![image](https://github.com/liyunyi1936/Stepper-motor-control/blob/master/images/connect1.png)

