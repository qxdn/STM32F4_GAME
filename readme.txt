实验器材:
	探索者STM32F4开发板，4.3TFT显示屏		
硬件资源:
	1,DS0(连接在PF9)
	2,串口1(波特率:115200,PA9/PA10连接在板载USB转串口芯片CH340上面)
	3,ALIENTEK 2.8/3.5/4.3/7寸TFTLCD模块(通过FSMC驱动,FSMC_NE4接LCD片选/A6接RS) 
	4,按键KEY0(PE4)
	3,触摸屏(TFTLCD模块自带了,IO状态为:T_PEN(PB1)/T_MOSI(PF11)/T_MISO(PB2)/T_SCK(PB0)/T_CS(PC13)) 

实验现象:
	1,开机时黑屏，出现little game，闪烁出现touch to start
	2,按下后同fly bird玩吧
	3，死亡后按下对应按键就可以重新开始
