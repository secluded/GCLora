# GCLora
An Arduino with a RFM95 Radio module capable of LoRa transmittions

Select "Lillypad Arduino USB" as the board type in the Arduino IDE
The GCLora board should automatically reconnect on another COM port for uploading code, 
then return to the orignal port on completion.
If this fails, double pressing the reset button will put it into upload mode, the led will pulse.

Pins RF Radio uses:<br>
MISO/MOSI/SCK (SPI)<br>
Version 1<br>
4(RST), 8(CS), A0(D0), 23(D1), A4(D2) is connectable by closing the jumper.<br>
Version 2 - enable use of Radiohead Library for non LoRaWan applications<br>
4(RST), 8(CS), 7(D0), 23(D1), A4(D2) is connectable by closing the jumper.<br>

For Australian use, please clone our Arduino/LMIC repo as it has the frequencies mapped correctly.
