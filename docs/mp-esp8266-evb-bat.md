# ESP8266-EVB-BAT with micropython

## Pins
The ESP8266-EVB-BAT is an addon board that has 2 connectors :
- The UEXT connector with 10 pins
- The CON1 connector with 20 pins


| MicroPython Pin Value | EVB-BAT Board Connector and Pin Number | ESP8266 Board Pin Name |
|--------|--------|--------|
|  0  |  CON1 / 16  |  GPIO 0  |
|  1  |  UEXT / 3  |  GPIO 1 |
|  2  |  UEXT / 6  |  GPIO 2  |
|  3  |  UEXT / 4  | GPIO 3  |
|  4  |  UEXT / 5  |  GPIO 4  |
|  5  |  CON1 / 15  |  GPIO 5  |
|  -  |  CON1 / 5  |  SD_CLK  |
|  -  |  CON1 / 9  |  SD_D0  |
|  -  |  CON1 / 7  |  SD_D1  |
|  -  |  CON1 / 6  |  SD_D2  |
|  -  |  CON1 / 10  |  SD_D3  |
|  -  |  CON1 / 8  |  SD_CMD  |
|  12  |  UEXT / 7  |  GPIO 12  |
|  13  |  UEXT / 8  |  GPIO 13  |
|  14  |  UEXT / 9  |  GPIO 14  |
|  15  |  UEXT / 10  |  GPIO 15  |
|  16  |  CON1 / 7  |  GPIO 16  |

The micropython pin value is the one used as parameter for machine.Pin class initialisation
