# UART-RS232
RS232 Receiver/Transmitter Verilog for FPGA

I share my RS232 solution based on FPGA. I tested my project on DE2-70. I hope that these source code can help you. 

I also designed a simple authentication module as the top layer. The function of the top-level module is to send the data to be sent.

In simulation mode, I assume one bit per 12 clocks.
![top_wave](https://github.com/very9s/UART-RS232/blob/master/top_wave.jpg)
In the synthesis process, variable clkNUM_bit should be set to the corresponding number of clocks per bit

---------------------------------

这是RS232 收发模块的verilog源代码。原理简单，代码也简单。 
同时我设计了一个简单的验证模块作为顶层。顶层模块的功能就是将收到的数据发送回去。
在仿真模式下，假设每12个周期一位。
在综合过程中，变量clkNUM_bit应设置为每位的相应时钟数。
