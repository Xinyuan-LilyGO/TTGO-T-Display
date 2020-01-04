# TTGO T-Display

![image](https://github.com/Xinyuan-LilyGO/TTGO-T-Display/blob/master/image/pinmap.jpg)
## 1.Uses the following dependency libraries:
For more informations see the sources
- [TFT_eSPI](https://github.com/Bodmer/TFT_eSPI)        
- [Button2](https://github.com/LennartHennigs/Button2)

## 2.TFT_eSPI settings
Settings are managed by the build tooling PlatformIO
- [TFT_eSPI settings](https://github.com/Bodmer/TFT_eSPI/blob/master/Tools/PlatformIO/Configuring%20options.txt)
- based on TFT_eSPI provided values in [User_Setups/Setup25_TTGO_T_Display.h](https://github.com/Bodmer/TFT_eSPI/blob/master/User_Setups/Setup25_TTGO_T_Display.h) 

## 3.Install
- [Install PlateformIO](https://docs.platformio.org/en/latest/installation.html#python-package-manager)
- PlatformIO will manage all required software for building (aka: plateform like esp32, dependencies like the above TFT_eSPI)

## 3.Build
- go to the directory of this project
- open a terminal
- build with : `pio run` (first time is long because it needs to download all the requirements)
- upload to the board (needs the borad connected using USB + appropriate user settings see installation) : `pio run --target upload`
- See th e`Serial` output : `pio device monitor --baud 115200`

## Pinout
| Name       | V18    |
| ---------- | ------ |
| TFT Driver | ST7789 |
| TFT_MISO   | N/A    |
| TFT_MOSI   | 19     |
| TFT_SCLK   | 18     |
| TFT_CS     | 5      |
| TFT_DC     | 16     |
| TFT_RST    | N/A    |
| TFT_BL     | 4      |
| I2C_SDA    | 21     |
| I2C_SCL    | 22     |
| ADC_IN     | 34     |
| BUTTON1    | 35     |
| BUTTON2    | 0      |
| ADC Power  | 14     |
