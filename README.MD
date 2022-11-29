# TTGO T-Display

## Quick start
1. Copy  **TFT_eSPI**  to the  **<C:\Users\Your User Name\Documents\Arduino\libraries>**  directory
2. Open **Arduino IDE,** find **TFT_eSPI** in the file and example, the **T-Display** factory test program is located at **TFT_eSPI -> FactoryTest**, you can also use other sample programs provided by TFT_eSPI
3 In the **Arduino IDE** tool options, select the development board  **ESP32 Dev Module**, **select Disable in the PSRAM option**, **select 4MB in the Flash Size option**, Other keep the default
4. Select the corresponding serial port. If you are not sure, please remove all the serial ports, leaving the board in the USB connection state, just select that one
5. Finally, click upload, the right arrow next to the tick

-------------------------

1. 拷贝  **TFT_eSPI**  到  **<C:\Users\你的用户名\Documents\Arduino\libraries>**  目录内
2. 打开**ArduinoIDE** , 在文件，示例中找到**TFT_eSPI**, T-Display出厂测试程序位于**TFT_eSPI -> FactoryTest**,你也可以使用其他TFT_eSPI提供的示例程序
3. 在**Arduino IDE** 工具选项中 ， 开发板选择 **ESP32 Dev Module**,**在PSRAM选项中选择Disable**， **Flash Size 选项中选择4MB** ，其它保持默认 
4. 选择对应的串行端口，如果不清楚请移除所有串行端口，之保留板子处于USB连接状态，选择那一个即可
5. 最后可点击上传即可，勾号旁边的向右箭头

-------------------------
## SD card connection
- Demonstrate how to use the second SPI device, using the SD card as a demonstration device
- 使用SD卡作为演示设备,演示如何使用第二个SPI设备
![](image/SD.jpg)

## Pinout
| Name       | V18    |
| ---------- | ------ |
| TFT Driver | ST7789 |
| TFT_MISO   | N/A    |
| TFT_MOSI   | 19     |
| TFT_SCLK   | 18     |
| TFT_CS     | 5      |
| TFT_DC     | 16     |
| TFT_RST    | 23     |
| TFT_BL     | 4      |
| I2C_SDA    | 21     |
| I2C_SCL    | 22     |
| ADC_IN     | 34     |
| BUTTON1    | 35     |
| BUTTON2    | 0      |
| ADC Power  | 14     |

