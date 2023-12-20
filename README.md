# dev_h7_pro
使用RT Studio 创建和编译的工程

## 创建工程

使用RT Studio创建基于STM32H747XI芯片的工程，串口配置为PA0-TX PA1-RX。

## 添加SDRAM

在board.h中添加#define BSP_USING_SDRAM，编译下载后，使用sdram_test测试读写文件情况。

![avatar](/png/sdram_test.png)
