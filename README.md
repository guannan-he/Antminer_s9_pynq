# Antminer_s9_pynq
transplant several overlays to s9_pynq board
# To build PYNQ image for antminer s9  
reference:  
[kangyuzhe666/zynq7010-pynq-2.5](https://github.com/kangyuzhe666/zynq7010-pynq-2.5)  
# How to build your overlays:
references:  
[overlay "adder" on xilinx forum](http://xilinx.eetrend.com/blog/2019/100016903.html)  
[overlay "adder" transplant to PYNQ-Z2](https://blog.csdn.net/qq_41467882/article/details/102007786)
# change log
* add overlay "base" 20201025  
[User Manual](https://github.com/guannan-he/Antminer_s9_pynq/blob/main/base/README.md)  
* add overlay "resizer" 20201025  
[User Manual](https://github.com/guannan-he/Antminer_s9_pynq/blob/main/resizer/README.md)  
references:  
[IP core](https://github.com/Xilinx/PYNQ-HelloWorld)  
[DMA](https://blog.csdn.net/alangaixiaoxiao/article/details/103958007)  
[Block design](https://www.element14.com/community/groups/fpga-group/blog/2020/03/24/image-processing-on-zc702-using-pynq)  
* add overlay "antminerGPIO"  20201026
[User Manual](https://github.com/guannan-he/Antminer_s9_pynq/blob/main/antminerGPIO/README.md)  
references:  
[use gpio](https://github.com/Xilinx/PYNQ_Workshop/blob/master/Session_4/2_axi_gpio.ipynb)  
[add gpio](https://zhuanlan.zhihu.com/p/52469205)  
[axi gpio](https://medium.com/%E9%AB%94%E9%A9%97%E4%BA%BA%E7%94%9F-touch-life/pynq-z2-led-button-switch-gpio-test-45c2c270fd2f)
