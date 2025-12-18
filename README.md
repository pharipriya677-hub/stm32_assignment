# stm32_assignment
This is a bare-metal project for the STM32F103C8T6 demonstrating:
100 HZ timer using TIM2
Timer triggered ADC conversation on channel 0(PA0)
ADC results transferred to memory via DMA
DMA transfer complete sends ADC result via UART (PA9)
Display ADC values on a serial terminal(putty)
## Hardware
STM32F103C8T6 ("Blackpill")
PA0 - Analog input
PA9 -UART TX to USB-UART adapter
## Features
Fully bare-metal
DMA-driven ADC to UART transfer
Timer-based ADC triggerering at100 HZ
UART output at 115200 baud.


