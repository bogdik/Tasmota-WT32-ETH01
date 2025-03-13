Program Version	14.15.0 (eth01) 
Folder for_build containts files for build

On this fw ETH start on first run

Windows
 ```python -m esptool --chip esp32c3 --port COM3 --baud 115200 --before default_reset --after hard_reset write_flash -z --erase-all --flash_mode dout --flash_freq 40m --flash_size detect 0x0 firmware.factory.bin```

Linux
```esptool --chip esp32c3 --port /dev/ttyUSB0 --baud 115200 --before default_reset --after hard_reset write_flash -z --erase-all --flash_mode dout --flash_freq 40m --flash_size detect 0x0 firmware.factory.bin```

### Close look (Right)
* Uart and jumper connection GIPIO9 and GND for flash

<img src="https://sun9-52.userapi.com/impg/KqByofx73VVOUoMHy8H10zN42UzHACjFjGmyEA/hol5mItR-7k.jpg?size=716x955&quality=95&sign=e2e2c1986b972d2c415fd65b20325c9c&type=album">
