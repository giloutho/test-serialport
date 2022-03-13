## test-serialport

The goal of this project is to verify the good integration of serialport in an Electron application initiated with Electron Forge. This project must run on different operating systems: MacOS intel, MacOS M1, Windows and Linux. 

This project is a fork of [electron-serialport](https://github.com/serialport/electron-serialport)

### Built With

* [Electron](https://www.electronjs.org/)
* [Electron-forge](https://github.com/electron-userland/electron-forge)
* [SerialPort](https://github.com/serialport)


## Installation and usage
 
Clone the repo
```sh
git clone https://github.com/giloutho/test-serialport
```

### Windows
Tests in progress

### Linux
Tested on Ubuntu. This works directly without problems. _"npm intall"_ and _"npm start"_.

### Mac Intel
Tested on MacOS 10.15 (Catalina). This works directly without problems. _"npm intall"_ and _"npm start"_.

### Mac Arm
Tested on MacOS 12.2 (Monterey). This works directly without problems. _"npm intall"_ and _"npm start"_.

### Versions
These tests were performed with : 
* Electron 17
* Electron-forge 6
* SerialPort 10.3

## Results
This test displays serial ports of the computer.

No problem to detect some GPS like Flymaster
