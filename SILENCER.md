|Componente|Función|Pin ESP32|Notas|
|---|---|---|---|
|**Pantalla OLED SH1107 (SPI)**|||Alimentación: 3.3 V|
||GND|GND|Tierra común|
||VCC|3.3V|⚠️ _No usar 5V_|
||SCL|GPIO18|SPI Clock (SCK)|
||SDA (MOSI)|GPIO23|SPI datos|
||RES|GPIO16|Reset|
||DC|GPIO17|Dato/Comando|
||CS|GPIO5|Chip Select|
|**Encoder rotativo EC11B**||||
||Señal A (CLK)|GPIO14|Pull-up 10kΩ externa a 3.3V|
||Señal B (DT)|GPIO27|Pull-up 10kΩ externa a 3.3V|
||Común C|GND||
||Pulsador interno (SW)|GPIO26|`LOW` cuando se pulsa|
|**Botón externo**|Botón adicional|GPIO12|`LOW` cuando se pulsa|
