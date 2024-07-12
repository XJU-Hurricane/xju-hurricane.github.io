# 2024Summer

红色代表在暑假必须掌握，绿色代表可以到学校再学，蓝色代表可以不学

- ### 基础知识（可能会比较难，但是要会，要不然有些代码你根本不知道他是怎么实现的。Frank的C语言课基本都有。可能暑假学不完。大概列一下，实际要学的要比这多）

  - <font color='red'>位操作(与或非，写入位与读出位)</font>
  - <font color='red'>卫语句</font>
  - <font color='red'>C库函数(如`(f)(s)(v)scanf, (f)(s)(v)printf,atoi,strcat,strtol`)</font>
  - <font color='red'>结构体与指针</font>
  - <font color='red'>栈内存与堆内存</font>
  - <font color='red'>枚举与状态机</font>
  - <font color='red'>数组与表驱动</font>
  - <font color='red'>函数指针与回调函数，事件处理框架</font>
  - <font color='gree'>`void* `与泛型编程</font>
  - <font color='gree'>规则引擎设计(规则映射)</font>
  - <font color='gree'>可变参数</font>

- ### 外设

  - <font color='red'>GPIO</font>
  - <font color='red'>ADC, DAC</font>
  - <font color='red'>I2C, SPI</font>
  - <font color='red'>Timer</font>
  - <font color='red'>CAN (必须熟练，要不然不会写电机驱动)</font>
  - <font color='gree'>USART + DMA (如何保证串口通信的可靠性)</font>

- ### 嵌入式组件

  - <font color='red'>FreeRTOS</font>
  - <font color='DodgerBlue'>其他RTOS(掌握操作系统核心原理后会发现其实都大同小异)</font>
  - <font color='DodgerBlue'>串口Debug(正点原子的USMART，先大概学一下，我打算基于这个升级一下)</font>

- ### 算法（学习一下原理，不要求写代码）

  - <font color='red'>全向轮底盘</font>
  - <font color='red'>麦轮底盘</font>
  - <font color='red'>舵轮底盘</font>
  - <font color='red'>机械臂</font>

- ### 开发工具与环境

  - <font color='red'>Git</font>
  - <font color='red'>VSCode</font>
  - <font color='gree'>CMSIS + Keil MDK v6 + RTE(主要我还没研究完)</font>
  - <font color='DodgerBlue'>工具链(弄懂这个可以不依赖任何IDE)</font>

- ### STM32深入（平时翻着手册学一下，如果遇到比较难的花点时间搞懂就行。不要用大量的时间从头看到尾，没意义，学完就忘。）

  - <font color='gree'>STM32地址映射(大概了解)</font>
  - <font color='gree'>ST HAL+LL库的配置和架构(简单了解)</font>
  - <font color='gree'>调试器的一些组件使用(ITM, Eventer Recoder等)</font>
  - <font color='DodgerBlue'>STM32外设寄存器</font>
  - <font color='DodgerBlue'>ARM Cortex内核与寄存器</font>
  - <font color='DodgerBlue'>STM32时钟树</font>

- ### 下面是我觉得比较有意思的东西，不要求学，自己没事可以玩一下，比如做个MP3，MP4，USB声卡，电子书，智能家居（用手机开关灯）。。。

  - USB
  - GUI，如LVGL(学习成本可能会比较高)
  - F(S)MC + SRAM + LCD + NAND Flash (如果使用GUI，建议学一下)
  - 以太网
  - 文件系统
  - ...