UART Driver for STM32 Microcontrollers
A robust UART driver implementation for STM32 development boards using CMSIS libraries
## Features
UART initialization with configurable baud rates (1200 - 115200+) and peripheral clock = 8MHz.
## Requirements
### Hardware
- Nucleo STM32 development board (STM32F303x series)
- Multimeter (optional for debugging)
### Software
- STM32CubeIDE or compatible toolchain
- RealTerm
## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/Asma-Prog-Eng/UART
   
2. Import project into STM32CubeIDE:
File → Import... → Existing Projects into Workspace

3. Rebuild project dependencies

## Usage
Initialization
UART2_init () ;
Transmitting Data
Receiving Data 


## Project Structure

├── Core
│   ├── Inc/         → uart_driver.h
│   ├── Src/         → uart_driver.c

## Troubleshooting

No data received:
- Verify baud rate settings
- Check TX/RX pin connections
- Ensure correct clock configuration

Garbage characters:
- Verify clock source accuracy
- Check voltage levels
- 
Overrun errors:
- Increase receive buffer size

## Known Limitations
Limited to 8-bit data words

## Contributing
Pull requests are welcome. For major changes, open an issue first.

## License
MIT License
Copyright (c) [2025] [Asma Askri]
