# Macro Yau's EAGLE Libraries

This repository includes PCB component libraries for selected electronic and electromechanical components.

## Components

- Energy Harvesting Power Management IC (energy-harvesting-pmic.lbr)
  - [STMicroelectronics STC3100](https://www.st.com/en/power-management/stc3100.html)
  - [Texas Instruments BQ25570](http://www.ti.com/product/bq25570)
  - [Texas Instruments TPS7A05](http://www.ti.com/product/TPS7A05)
- Energy Harvesting Transducer (energy-harvesting-transducer.lbr)
  - IXYS KXOB22 Series Solar Cell
- Energy Storage (energy-storage.lbr)
  - Keystone Electronics 1024 SMT AA Cell Holder
- [Espressif Systems ESP32 SoC](http://www.espressif.com/en/products/hardware/esp32/overview) (esp32.lbr)
  - Ai-Thinker ESP3212 _(Obsolete)_
  - Ai-Thinker ESP-32S
  - Espressif Systems ESP-WROOM-32
- [Espressif Systems ESP8266 SoC](https://www.espressif.com/en/products/hardware/esp8266ex/overview) (esp8266.lbr)
  - Ai-Thinker ESP-12E
  - Espressif Systems ESP-WROOM-02

## Installation

Download the latest [ZIP file](https://github.com/MacroYau/MacroYau-EAGLE-Libraries/archive/master.zip) (or via Git) and extract the `MacroYau-EAGLE-Libraries` folder to the `lbr` folder inside your EAGLE installation directory. By default, the installation location should be:

- `/Applications/EAGLE-9.0.1/lbr` (macOS)
- `C:\Program Files\EAGLE-9.0.1\lbr` (Windows)

If you prefer to keep custom libraries in a separate directory to avoid migration during every EAGLE version update, you can refer to [this tutorial](https://github.com/adafruit/Adafruit-Eagle-Library).

## Compatibility

The libraries are created with [EAGLE 9.0.1](https://www.autodesk.com/products/eagle/overview) and should be compatible with newer versions.

## License

[Creative Commons Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/)
