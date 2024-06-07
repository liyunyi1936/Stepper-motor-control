## 环境依赖

+ Keil v5.31

+ STM32cubeMX6.1.0

## 主控芯片

STM32F103 C8T6


## 目录结构描述

* [doc]()
  * [databook]()
  * [schematic]()
* [src]()
  * [adc_data ]()
  * [dichotomous_search]() 
  * [dichotomous_ search _visitor _mode]()  
  * [get_ real _temp _value]() 
  * [ntc_table]() 
  * [median_filter]() 
* [template]()
* [.gitignore]()
* [readme]()


## 功能概述

- TIM2发送1k hz的占空比90%的pwm控制步进电机转动

### - IO口对应说明

PA1     ------> TIM2_CH2

​