# Pycom ESP32 Universal Firmware

## Installation

Make sure you have [Pycom's official firmware tool](https://docs.pycom.io/advance/cli/) installed. 

#### Linux
```bash
$ pycom-fwtool-cli --port /dev/ttyUSB0 erase_all
$ pycom-fwtool-cli -r --port /dev/ttyUSB0 flash --tar ESP32-4MB-1.20.2.rc11.tar.gz
```
#### Windows
```PowerShell
# make sure you adjust the com port
> pycom-fwtool-cli.exe --verbose --port COM4 erase_all
> pycom-fwtool-cli.exe -r --verbose --port COM4 flash --tar ESP32-4MB-1.20.2.rc11.tar.gz
```
### Refer to the [Pycom doc's](https://docs.pycom.io/) for usage.
Note: for pins, use 'GPIOxx' or 'GPIxx' instead of 'Pxx' as outlined in the docs.

## License
[MIT](https://choosealicense.com/licenses/mit/)