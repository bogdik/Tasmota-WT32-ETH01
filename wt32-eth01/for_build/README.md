# Tasmota for WT32-ETH01

This project provides the necessary files and instructions to build and flash Tasmota version 14.3.0.7 onto the WT32-ETH01 board. It supports Ethernet functionality and includes configurations for PlatformIO and flashing scripts.

---

## Repository Contents

- **`tasmota`**: Contains 2 files my_user_config.h and user_config_override.h need replace 
- **`partitions`**: Contains memory layout files for ESP32. huge_app.csv upload
- **`build_cmd.sh`**: A script for automated build and flashing. cmd for build `platformio run -e wt32-eth01`
- **`platformio_tasmota_env32.ini`**: PlatformIO environment configuration for WT32-ETH01. replace this file

---

## Requirements

- **Hardware**:
  - WT32-ETH01 board
  - USB-UART adapter
  - 5V power source
- **Software**:
  - [PlatformIO](https://platformio.org/) for building the firmware or use gitpod.io
  - [esptool.py](https://github.com/espressif/esptool) for flashing the device

---

## How to Use
Need github account 

create account on https://www.gitpod.io/

After you successfully sign in, you can start your personal project. The fastest way to load Tasmota into Gitpod is with one of the following links:

    Development Branch: https://gitpod.io#https://github.com/arendst/Tasmota/tree/development
    
    Master Release: https://gitpod.io#https://github.com/arendst/Tasmota/tree/master
    
    TasmoCompiler: https://gitpod.io/#https://github.com/benzino77/tasmocompiler

after create after creating spaces with source files replace files and run `platformio run -e wt32-eth01`
