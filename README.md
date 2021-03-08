# Adafruit BME280 Library [![Build Status](https://github.com/TINLES2021/Adafruit_BME280_Library/workflows/Arduino%20Library%20CI/badge.svg)](https://github.com/TINLES2021/Adafruit_BME280_Library/actions)

This is a library for the Adafruit BME280 Humidity, Barometric Pressure + Temp sensor

Designed specifically to work with the [Adafruit BME280 Breakout](http://www.adafruit.com/products/2652). We are currently using the [BME 280 Breakout](https://shop.pimoroni.com/products/bme280-breakout).

*Adafruit invests time and resources providing this open source code, please support Adafruit and open-source hardware by purchasing products from Adafruit!*

# Installation
In the Energia IDE, navigate to Sketch > Include Library > Add .ZIP Library. At the top of the drop down list, select the option to "Add .ZIP Library". Here you can select this ZIP file.

If you want to contribute to this repository, there is a better way. Please see [Contributing](#Contributing)

## Dependencies
Because this library is not installed via the built-in Library Manager, the dependency will also not be installed manually. Therefore, you will have to install that as well. Please download the ZIP from their repository to get the latest version.

 * [Adafruit Unified Sensor Driver](https://github.com/adafruit/Adafruit_Sensor)

# Contributing
Contributions are welcome! Please stay civil.

If you want to use this library in Energia while contributing, the easiest way is to clone this repository in your libraries folder.

```bash
git clone https://github.com/TINLES2021/Adafruit_BME280_Library.git
```

Please note that you have to be a contributor of TINLES2021 to push to this repository. If you are not, then you will have to fork first.

## Formatting and clang-format
This library uses [`clang-format`](https://releases.llvm.org/download.html) to standardize the formatting of `.cpp` and `.h` files.
Contributions should be formatted using `clang-format`:

The `-i` flag will make the changes to the file.
```bash
clang-format -i *.cpp *.h
```
If you prefer to make the changes yourself, running `clang-format` without the `-i` flag will print out a formatted version of the file. You can save this to a file and diff it against the original to see the changes.

Note that the formatting output by `clang-format` is what the automated formatting checker will expect. Any diffs from this formatting will result in a failed build until they are addressed. Using the `-i` flag is highly recommended.

### clang-format resources
  * [Binary builds and source available on the LLVM downloads page](https://releases.llvm.org/download.html)
  * [Documentation and IDE integration](https://clang.llvm.org/docs/ClangFormat.html)

## About this Driver
Written by Ladyada for Adafruit Industries.

BSD license, check license.txt for more information

All text above must be included in any redistribution
