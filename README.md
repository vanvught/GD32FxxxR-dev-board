
[PayPal.Me Donate](https://paypal.me/AvanVught?locale.x=nl_NL)

-----------

# GD32F103R GD32F107R GD32F207R GD32F407R development board

This board can be used with the `GD32F103Rx` and the `GD32F107Rx` , `GD32F207Rx`, `GD32F407Rx` (Ethernet) MCU's. 

Please note that the crystal for the `GD32F107Rx`, `GD32F207Rx` and the `GD32F407Rx` is `25MHz` and the crystal for the `GD32F103Rx` is `8MHz`.

The USB is power and DFU.

The 2x13 header is pin compatible with the Orange Pi Zero and Raspberry Pi boards. 

<table style="width:100%">
	<tr><th colspan="8">2x13 Header</th>
	</tr>
	<tr>
	<td></td>
	<td colspan="2" style="background-color:#FFA500">3.3V PWR</td>
	<td>1</td>
	<td>2</td>
	<td rowspan="2" colspan="2" style="background-color:#FF0000">5V PWR</td>
	<td rowspan="2"></td>
	</tr>
	<tr>
	<td rowspan="2">REMAP = 1 / AF4</td>
	<td style="background-color:#EE82EE">I2C0 SCA</td>
	<td>PB9</td>
	<td>3</td>
	<td>4</td>
	</tr>
	<tr>
	<td style="background-color:#EE82EE">I2C0 SCL</td>
	<td>PB8</td>
	<td>5</td>
	<td>6</td>
	<td colspan="2">GND</td>
	<td></td>
	</tr>
	<tr>
	<td colspan="2"></td>
	<td>PA6</td>
	<td>7</td>
	<td>8</td>
	<td>PC10</td>
	<td style="background-color:#4169E1">USART2 TX</td>
	<td rowspan="2">REMAP [1:0] =“01” (partial remap) / AF7</td>
	</tr>
	<tr>
	<td></td>
	<td colspan="2">GND</td>
	<td>9</td>
	<td>10</td>
	<td>PC11</td>
	<td style="background-color:#4169E1">USART2 RX</td>
	</tr>
	<tr>
	<td rowspan="2">REMAP = 0</td>
	<td style="background-color:#4169E1">USART5 RX</td>
	<td>PC7</td>
	<td>11</td>
	<td>12</td>
	<td>PB10</td>
	<td colspan="2"></td>
	</tr>
	<tr>
	<td style="background-color:#4169E1">USART5 TX</td>
	<td>PC6</td>
	<td>13</td>
	<td>14</td>
	<td colspan="2">GND</td>
	<td></td>
	</tr>
	<tr>
	<td colspan="2"></td>
	<td>PB14</td>
	<td>15</td>
	<td>16</td>
	<td>PB15</td>
	<td colspan="2"></td>
	</tr>
	<tr>
	<td></td>
	<td colspan="2" style="background-color:#FFA500">3.3V PWR</td>
	<td>17</td>
	<td>18</td>
	<td>PA13</td>
	<td style="background-color:#F0FFFF">SWDIO</td>
	<td></td>
	</tr>
	<tr>
	<td></td>
	<td style="background-color:#00F000">SPI2 MOSI</td>
	<td>PB5</td>
	<td>19</td>
	<td>20</td>
	<td colspan="2">GND</td>
	<td></td>
	</tr>
	<tr>
	<td></td>
	<td style="background-color:#00F000">SPI2 MISO</td>
	<td>PB4</td>
	<td>21</td>
	<td>22</td>
	<td>PA11</td>
	<td colspan="2"></td>
	</tr>
	<tr>
	<td></td>
	<td style="background-color:#00F000">SPI2 SCK</td>
	<td>PB3</td>
	<td>23</td>
	<td>24</td>
	<td>PA15</td>
	<td style="background-color:#00F000">SPI2 CS</td>
	<td></td>
	</tr>
	<tr>
	<td></td>
	<td colspan="2">GND</td>
	<td>25</td>
	<td>26</td>
	<td>PA14</td>
	<td style="background-color:#F0FFFF">SWCLK</td>
	<td></td>
	</tr>
</table>

[Colour version](https://htmlpreview.github.io/?https://github.com/vanvught/GD32F103R-GD32F107R-GD32F207R-GD32F407R-dev-board/blob/main/html/header-2x13.html)

<table>
<tr><th colspan="4">1x13 Header</th></tr>
	<tr>
	<td>1</td>
	<td colspan="2">NC</td>
	</tr>
	<tr>
	<td>2</td>
	<td colspan="2">GND</td>
	</tr>
	<tr>
	<td>3</td>
	<td>PA14</td>
	<td style="background-color:#F0FFFF">SWCLK</td>
	</tr>
	<tr>
	<td>4</td>
	<td colspan="2">GND</td>
	</tr>
	<tr>
	<td>5</td>
	<td>PA13</td>
	<td style="background-color:#F0FFFF">SWDIO</td>
	</tr>
	<tr>
	<td>6</td>
	<td colspan="2">NRST</td>
	</tr>
	<tr>
	<td>7</td>
	<td>PA5</td>
	<td style="background-color:#FFFFEF">DAC1</td>
	</tr>
	<tr>
	<td>8</td>
	<td>PA4</td>
	<td style="background-color:#FFFFEF">DAC0</td>
	</tr>
	<tr>
	<td>9</td>
	<td>PC12</td>
	<td style="background-color:#4169E1">UART4 TX</td>
	</tr>
	<tr>
	<td>10</td>
	<td>PD2</td>
	<td style="background-color:#4169E1">UART4 RX</td>
	</tr>
	<tr>
	<td>11</td>
	<td>PB6</td>
	<td style="background-color:#4169E1">USART0 TX</td>
	<td rowspan="2">REMAP = 1 / AF7</td>
	</tr>
	<tr>
	<td>12</td>
	<td>PB7</td>
	<td style="background-color:#4169E1">USART0 RX</td>
	</tr>
	<tr>
	<td>13</td>
	<td colspan="2">GND</td>
	</tr>
</table>

[Colour version](https://htmlpreview.github.io/?https://github.com/vanvught/GD32F103R-GD32F107R-GD32F207R-GD32F407R-dev-board/blob/main/html/header-1x13.html)

<table>
	<tr><th colspan="2">Boot UART</th></tr>
	<tr>
	<td>1</td>
	<td>GND</td>
	</tr>
	<tr>
	<td>2</td>
	<td style="background-color:#4169E1"> USART0 RX</td>
	<td>PA10</td>
	<td rowspan="2">REMAP = 0</td>
	</tr>
	<tr>
	<td>3</td>
	<td style="background-color:#4169E1"> USART0 TX</td>
	<td>PA9</td>
	</tr>	
</table>

<table>
<head>
	<tr>
	<th colspan="2">LED's</th>
	</tr>
</head>
<tbody>
	<tr>
	<td>1</td>
	<td>PC0</td>
	</tr>
	<tr>
	<td>2</td>
	<td>PC2</td>
	</tr>
	<tr>
	<td>3</td>
	<td>PC3</td>
	</tr>
	<tr>
	<td>4</td>
	<td>3V3</td>
	</tr>	
</tbody>
</table>

<table>
<head>
	<tr>
	<th colspan="2">J5</th>
	</tr>
</head>
<tbody>
	<tr>
	<td>1</td>
	<td>PC8</td>
	</tr>
	<tr>
	<td>2</td>
	<td>PC9</td>
	</tr>
	<tr>
	<td>3</td>
	<td>PC13</td>
	</tr>
</tbody>
</table>

### GD32F103Rx (only)

<table>
	<tr><th colspan="4">2x7 Header</th></tr>
	<tr>
	<td>PB13</td>
	<td>1</td>
	<td>2</td>
	<td>NC</td>
	</tr>
	<tr>
	<td>PB11</td>
	<td>3</td>
	<td>4</td>
	<td>PB12</td>
	</tr>
	<tr>
	<td>PC4</td>
	<td>5</td>
	<td>6</td>
	<td>PC5</td>
	</tr>
	<tr>
	<td>PA1</td>
	<td>7</td>
	<td>8</td>
	<td>PA7</td>
	</tr>
	<tr>
	<td>PA2</td>
	<td>9</td>
	<td>10</td>
	<td>PC1</td>
	</tr>
	<tr>
	<td>GND</td>
	<td>11</td>
	<td>12</td>
	<td>GND</td>
	</tr>
	<tr>
	<td style="background-color:#FFA500">3V3</td>
	<td>13</td>
	<td>14</td>
	<td style="background-color:#FFA500">3V3</td>
	</tr>	
</table>

### GD32F103Rx (only)
<table>
<head>
<tr><th colspan="5">1x4 Header</th></tr>
</head>
<tbody>
<tr>
<td></td>
<td>GND</td>
<td>1</td>
<td>GND</td>
<td></td>
</tr>
<tr>
<td></td>
<td style="background-color:#FFA500">3V3</td>
<td>2</td>
<td style="background-color:#FFA500">3V3</td>
<td></td>
</tr>
<tr>
<td rowspan="2">REMAP[1:0] = 00/01 / AF4</td>
<td style="background-color:#EE82EE">I2C1 SCL</td>
<td>3 | PB10</td>
<td style="background-color:#4169E1">USART2 RX</td>
<td rowspan="2">REMAP = 0 (no remap)</td>
</tr>
<tr>
<td style="background-color:#EE82EE">I2C1 SCA</td>
<td>4 | PB11</td>
<td style="background-color:#4169E1">USART2 TX</td>
</tr>	
</tbody>
</table>

[Colour version](https://htmlpreview.github.io/?https://github.com/vanvught/GD32F103R-GD32F107R-GD32F207R-GD32F407R-dev-board/blob/main/html/header-1x4.html)

### GD32F107Rx GD32F207Rx GD32F407Rx (only)

<table>
<head>
<tr>
<th colspan="4">External-PHY</th>
</tr>
</head>
<tbody>
<tr>
<td>RMII TXD1</td>
<td>1</td>
<td>2</td>
<td>NC</td>
</tr>
<tr>
<td>RMII TX_EN</td>
<td>3</td>
<td>4</td>
<td>RMII TXD0</td>
</tr>
<tr>
<td>RMII RXD0</td>
<td>5</td>
<td>6</td>
<td>RMII RXD1</td>
</tr>
<tr>
<td>RMII REF_CLK</td>
<td>7</td>
<td>8</td>
<td>RMII CRS_DV</td>
</tr>
<tr>
<td>MDIO</td>
<td>9</td>
<td>10</td>
<td>MDC</td>
</tr>
<tr>
<td>GND</td>
<td>11</td>
<td>12</td>
<td>GND</td>
</tr>
<tr>
<td style="background-color:#FFA500">3V3</td>
<td>13</td>
<td>14</td>
<td style="background-color:#FFA500">3V3</td>
</tr>		
</tbody>
</table>

![](https://github.com/vanvught/GD32F103R-GD32F107R-GD32F207R-GD32F407R-dev-board/blob/main/GD32F103R-GD32F107R-GD32F207R-GD32F407R-dev-board.png)

# Add-on
Pixel 8x 4 Universes for the `GD32F207RG` / `GD32F407RE` -> ![](https://github.com/vanvught/GD32F103R-GD32F107R-GD32F207R-GD32F407R-dev-board/blob/main/Addon/Pixel8x4U.png)