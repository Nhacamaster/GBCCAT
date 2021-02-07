# GBCCAT
GBCCAT - Gameboy Color Emulator based on GNUBOY,
still in development, used hardware is ESP32 WROVER chip, ST7789 1.3" LCD 240*240px,
loading games from microSD card, emulator has been controlled by PS2 (USB) keyboard.

Also You need disable fix PSRAM cache: 
in file (for example): C:\Users\<MYUSERNAME>\AppData\Local\Arduino15\packages\esp32\hardware\esp32\1.0.3\boards.txt

```shell
#esp32.menu.PSRAM.enabled.build.defines=-DBOARD_HAS_PSRAM -mfix-esp32-psram-cache-issue
esp32.menu.PSRAM.enabled.build.defines=-DBOARD_HAS_PSRAM
```

![Image description](https://github.com/nathalis/GBCCAT/raw/main/media/GBCCAT.gif)

![Image description](https://github.com/nathalis/GBCCAT/raw/main/hardware/ncat_sch.png)

![Image description](https://github.com/nathalis/GBCCAT/raw/main/hardware/ncat_brd.png)

![Image description](https://github.com/nathalis/GBCCAT/raw/main/media/IMG_20210112_200409.jpg)
![Image description](https://github.com/nathalis/GBCCAT/raw/main/media/IMG_20210112_200439.jpg)
![Image description](https://github.com/nathalis/GBCCAT/raw/main/media/IMG_20210112_200459.jpg)
![Image description](https://github.com/nathalis/GBCCAT/raw/main/media/IMG_20210112_200510.jpg)
![Image description](https://github.com/nathalis/GBCCAT/raw/main/media/IMG_20210112_201024.jpg)
![Image description](https://github.com/nathalis/GBCCAT/raw/main/media/IMG_20210112_201043.jpg)


