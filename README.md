# IoT Hackathon 2019

## Installation Guides

Each team received a box of hardware, including two separate micro-controllers (Azure Sphere or Feather Huzzah) as well as sensors, leds, wires, etc. The installation guides for both micro-controller are listed below.

## Azure Sphere Hardware Installation

Installation Guide for Windows 10 machines:
* Download Visual Studio 2017, version 15.7 or later: https://docs.microsoft.com/en-us/visualstudio/releasenotes/vs2017-relnotes-v15.7
* Download the Azure Sphere SDK for Visual Studio Preview: https://aka.ms/AzureSphereSDKDownload

Installation Guide for Mac OS machines: https://drive.google.com/file/d/1UvfDjtJJC_HCPok1Y_vY2wal0zwIhk0c/view?usp=sharing

## AdaFruit Hardware Installation

### Hardware + What to Install

In addition to the Microsoft Azure Sphere, we also have hardware available from Adafruit ([hardware list](https://www.adafruit.com/wishlists/457925)).

You will need to install the **Arduino IDE** to program the device. Depending on your operating system, you may require drivers for the
**Feather HUZZAH**. Follow the instructions [here](https://learn.adafruit.com/adafruit-feather-huzzah-esp8266/using-arduino-ide) to install drivers and run the *Blink Test* and the *Connecting via WiFi* to make sure your system and WiFi are set up correctly.

### Install Steps
These instructions largely follow https://learn.adafruit.com/adafruit-feather-huzzah-esp8266/using-arduino-ide You can find more details and screenshots there.

1. Install the CP2104 VCP Drivers (not necessary for Linux): https://www.silabs.com/products/development-tools/software/usb-to-uart-bridge-vcp-drivers
2. Install the Arduino IDE: https://arduino.cc/download
- Add ESP8266 boards
- There's a text box under "Preferences > Additional Board Manager URLs". In the text box, enter http://arduino.esp8266.com/stable/package_esp8266com_index.json
- Tools -> Board -> Board Manager – Search for ESP8266, then click the Install button.
3. Run Blink Code
- File > Examples > ESP8266 > Blink
- Click Verify (If you don’t have a device)
- Click Upload (If you do have a device)

Adafruit has several setup tutorials, videos, and articles available to help you familiarize yourself with the platform.
- [Setup and Hello World](https://learn.adafruit.com/adafruit-io-basics-esp8266-arduino?view=all)
- [Adafruit IO Guides](https://www.adafruit.com/product/2680#tab_learn)
- [learn.adafruit.com](https://learn.adafruit.com/)

## Communication

Please make sure you sign up for the [WWCode Portland Slack community](https://bitly.com/wwcpdx-slack) and join the 
[#hackathon-2019]() channel. 
