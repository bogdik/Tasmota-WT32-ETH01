Program Version	14.15.0 (eth01) 
Folder for_build containts files for build

On this fw ETH start on first run

Windows
 ```python -m esptool --chip esp32c3 --port COM3 --baud 115200 --before default_reset --after hard_reset write_flash -z --erase-all --flash_mode dout --flash_freq 40m --flash_size detect 0x0 firmware.factory.bin```

Linux
```esptool --chip esp32c3 --port /dev/ttyUSB0 --baud 115200 --before default_reset --after hard_reset write_flash -z --erase-all --flash_mode dout --flash_freq 40m --flash_size detect 0x0 firmware.factory.bin```

### Close look (Right)
* Uart and jumper connection

<img src="https://s214vla.storage.yandex.net/rdisk/801f4405220a6d49de32f252d2c5dbf8b47fdd93196c2ded3e5972c2818c374a/67c37aec/oo2Pr-rO6druIpfEhwtV-h3Hl4qhnJfRcylbUDV8MOJIuE7o5oGYWHYP7n6mju-rQfKNk8Oay9qcQOLH42l4Pg==?uid=0&filename=2025-03-01%2020-05-48.png&disposition=inline&hash=&limit=0&content_type=image%2Fpng&owner_uid=0&fsize=728351&hid=23af63ef5ae35b30030d0032d9b07139&media_type=image&tknv=v2&etag=fe06bd8df4da263f3dfa792ba4b1db6f&ts=62f4e8a639300&s=68e0147ecf78a1074c5e08e83fbc24bb29f8572ee35ee1853470bbccaa4f9702&pb=U2FsdGVkX19NRa4ICa9_hlzUl6L9YTeY1kOYver0oVLW8PmU5YQ0_KjzCcU94sz5zLXeGRaaFrEECs5poleUrpBCZogsFqJi0r8vQvQO4EY">
