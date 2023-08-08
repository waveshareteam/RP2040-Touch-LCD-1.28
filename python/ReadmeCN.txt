/*****************************************************************************
* | File      	:   Readme_CN.txt
* | Author      :   
* | Function    :   Help with use
* | Info        :
*----------------
* |	This version:   V1.0
* | Date        :   2023-01-10
* | Info        :   在这里提供一个中文版本的使用文档，以便你的快速使用
******************************************************************************/
这个文件是帮助您使用本例程。
在这里简略的描述本工程的使用：

1.基本信息：
本例程使用1.28inch Touch LCD进行了验证，你可以在工程的中查看对应的测试例程;

2.管脚连接：
管脚连接你可以在1.28inch_Touch_LCD.py查看，这里也再重述一次：

LCD  	=>	    Pico
VCC    	->    	3.3V
GND    	->    	GND
MISO    ->    	12
MOSI    ->    	11
SCLK    ->    	10
LCD_CS  ->    	9
LCD_DC  ->    	14
LCD_RST ->    	8
LCD_BL  ->    	15

Touch  	=>	    Pico    
TP_SDA  ->      6
TP_SCL  ->      7
TP_INT  ->      16
TP_RST  ->      17


3.基本使用：
    1): 按住Pico板上的按键，将pico通过Micro USB线接到电脑的USB接口，然后松开按键。
        接入之后，电脑会自动识别到一个可移动盘（RPI-RP2）
        
    2): 将python目录中rp2-pico-20221125-v1.19.1.uf2 文件复制到识别的可移动盘（RPI-RP2）中
    
    3): 更新Thonny IDE
        sudo apt upgrade thonny
        
    4): 打开Thonny IDE （点击树莓logo -> Programming -> Thonny Python IDE ）
        选择Tools -> Options... -> Interpreter
        选择MicroPython(Raspberry Pi Pico 和ttyACM0端口
        
    5): 在Thonny IDE中打开python/1.28inch_Touch_LCD.py文件
        然后运行当前脚本（绿色小三角）即可
    