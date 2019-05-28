# AXI_DMA_Custom_IP
Transfer data from DDR memory to AXIS asynchronous FIFO and back through AXI DMA
***
## Getting Start (Experiment Setup)
+ Windows 7/8/8.1/10 64-bit
+ Xilinx Vivado 2016/17/18.X (must include SDK)
+ [Board definition files](http://microzed.org/support/documentation/1519) for MicroZed 70X0
+ USB to micro USB cable x 1 
+ USB to mini USB cable x 1 (for JTAG)
+ [Putty.exe](https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html)

## System Overview
本實驗將透過[AXI DMA (Direct Memory Access)](https://www.xilinx.com/support/documentation/ip_documentation/axi_dma/v7_1/pg021_axi_dma.pdf) 結合自製的Stream Data FIFO完成I/O Device與DDRX Memory之間的資料傳輸。如未完成上一則[AXI_DMA_FIFO](https://github.com/absolutezero2730/AXI_DMA_FIFO)實作練習的朋友，建議先完成以後再開始本實驗，方能對DMA有更深刻的印象與了解。

Block diagram (Compatible with the above two Modes)：

<img src="https://github.com/absolutezero2730/AXI_DMA_Custom_IP/blob/master/picture/Design%20Overview.png" width="80%" height="80%">
