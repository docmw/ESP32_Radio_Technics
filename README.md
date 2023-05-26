Modified version of the design by Ezelf:
https://github.com/Edzelf/ESP32Radio-V2
Introduced changes:
-included plugin for VS1053 to play .flac files
-adding flac and ogg files to the list
-support for SD cards in SD_MMC mode
-removed mqtt support
-use of the IRremote library for remote operation from any remote control
-integration with Technics ST-GT350 tuner: FM frequency reading, use of existing buttons, rotary encoder and IR sensor
-displaying RDS services for FM stations from Technics tuner
To do:
-added FM Tuner mode
-turning off the FM tuner microcontroller when not in use
-playing music from DLNA servers
-play music from Bluetooth
-cleaning and organizing the code
