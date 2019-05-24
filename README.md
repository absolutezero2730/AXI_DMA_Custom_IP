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
本實驗將透過[AXI DMA (Direct Memory Access)](https://www.xilinx.com/support/documentation/ip_documentation/axi_dma/v7_1/pg021_axi_dma.pdf) 結合自製的Stream Data FIFO完成I/O Device與DDRX Memory之間的資料傳輸。建議先玩
