# Waveshare EPD 1.54in ESP8266 Demo

Platform IO Demo project based on [Waveshares E-Paper_ESP8266_Driver_Board_Code](https://www.waveshare.com/wiki/File:E-Paper_ESP8266_Driver_Board_Code.7z).
The librarys `src` from the zip was moved into `lib/waveshare` and the code from `examples/epd1in54-demo` was moved into `src` and renamed to `main.cpp`.

The wiring on a WeMos D1 Mini R2 or other ESP8266 based board is as following:

| EPD Pin | WeMos Pin | Other ESP8266 based Pin |
| ------- | --------- | ----------------------- |
| CS      | D8        | 15                      |
| RST     | D4        | 2                       |
| DC      | D2        | 4                       |
| BUSY    | D1        | 5                       |
| DIN     | D7        | 13                      |
| CLK     | D5        | 14                      |
