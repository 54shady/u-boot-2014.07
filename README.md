u-boot-2014.07
==============

u-boot-2014.07 for mini2440

# means in host
> means in uboot

Usage 1(v0.1): uart clk
	# make mini2440_config
	# make ARCH=arm CROSS_COMPILE=arm-linux-
	
	> loady 32000000
	> go 32000000

Usage 2(v0.2): nor flash
	> loady 32000000
	> go 32000000

Usage 3(v0.3): dm9k is work
	> loady 32000000
	> go 32000000

Usage 4(v0.4): nand flash read and write support
	> loady 32000000
	> go 32000000
