# STM32F1 DAPLink

A CMSIS-DAP compliant debugger based on STM32F1

## Features

* CMSIS-DAP V2.1
* SWD
* JTAG
* UART
* Connected & Running LED

## Usage

| Function | Label | GPIO |
|:-|:-:|:-:|
| JTAG_TDI | TDI | A1 |
| JTAG_TDO | TDO | A5 |
| JTAG_TMS | TMS  | A6 |
| JTAG_TCK | TCK  | A4 |
| SWD_SWDIO | TMS | A6 |
| SWD_SWCLK | TCK | A4 |
| nRESET | RTS | A0 |
| UART TX | TX | A9 |
| UART RX | RX | A10 |

Notice that 3.3V level I/O is required.

## Compile and download
First clone the project, then use keil to compile and download it to the target board

## Clone
```

git clone https://github.com/HaiMianBBao/CherryUSB-STM32F1-DAPLink.git
cd CherryUSB-STM32F1-DAPLink
git submodule update --init --recursive


```

## Renderings

![DEBUG](img/debug.png)
![UART](img/uart.jpg)