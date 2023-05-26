Modified version of the design by Ezelf:<br />
https://github.com/Edzelf/ESP32Radio-V2<br />
Introduced changes:<br />
-included plugin for VS1053 to play .flac files<br />
-adding flac and ogg files to the list<br />
-support for SD cards in SD_MMC mode<br />
-removed mqtt support<br />
-use of the IRremote library for remote operation from any remote control<br />
-integration with Technics ST-GT350 tuner: FM frequency reading, use of existing buttons, rotary encoder and IR sensor<br />
-displaying RDS services for FM stations from Technics tuner<br />

To do:<br />
-add FM Tuner mode<br />
-add RDS services display on LCD<br />
-turning off the FM tuner microcontroller when not in use<br />
-playing music from DLNA servers<br />
-play music from Bluetooth<br />
-cleaning and organizing the code<br />
