/*****************************************************************************
* | File      	:   Readme_EN.txt
* | Author      :   
* | Function    :   Help with use
* | Info        :
*----------------
* |	This version:   V1.0
* | Date        :   2022-06-23
* | Info        :   Here is an English version of the documentation for your quick use.
******************************************************************************/
This file is to help you use this demo.
Here is a brief description of the use of this project:

1. Basic information:
This demo is verified using 1.28inch Touch LCD. 
You can view the corresponding test demo in the project;

2. Pin connection:
You can check the pin connection at 1.28inch_Touch_LCD.py, and repeat it here:

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


3. Basic use:
    1): Press and hold the button on the Pico board, connect Pico to the USB port of the 
        computer through the Micro USB cable, and then release the button.
        After connecting, the computer will automatically recognize a removable disk (RPI-RP2)
        
    2): Copy the pico_micropython_20210121.uf2 file in the python directory to the recognized 
        removable disk (RPI-RP2)
    
    3): Update Thonny IDE
        sudo apt upgrade thonny
        
    4): Open Thonny IDE （Click raspberry logo -> Programming -> Thonny Python IDE ）
        select Tools -> Options... -> Interpreter
        select MicroPython(Raspberry Pi Pico  and ttyACM0 port
        
    5): Open the python/1.28inch_Touch_LCD.py file in Thonny IDE
        Then run the current script (green triangle)
    