# TTGO T-Display

## 1.Install the following dependency library files:
- [TFT_eSPI](https://github.com/lewisxhe/TFT_eSPI)
- [Button2](https://github.com/lewisxhe/Button2)


## 2.TFT_eSPI settings
- Move or copy `User_Setups/TTGO_T_Display.h` to `TFT_eSPI/User_Setups/`
- Add `#include <User_Setups/TTGO_T_Display.h>` to  `TFT_eSPI/User_Setup_Select.h`
  

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
| TFT_BL     | 14     |
| I2C_SDA    | 21     |
| I2C_SCL    | 22     |
| ADC_IN     | 34     |
| BUTTON1    | 35     |
| BUTTON2    | 0      |
