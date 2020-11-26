HP Spectre x360 13-4104ng Hackintosh
====================================

Specs
-----

[hw-probe](https://linux-hardware.org/index.php?probe=d258888474)

|   |  |
| --- | ---|
| CPU | Intel® Core™ i5-6200U (Skylake, 2.3 GHz, up to 2.8 GHz, 3 MB cache, 2 cores) |
| GPU | Intel® HD Graphics 520 |
| RAM | 8 GB Samsung DDR3L on-board |
| Display | LG 13.3" QHD IPS LED-backlit touch screen (2560x1440) |
| Touchpad | HP Control Zone (Synaptics SynPS/2, `SYN3206`/`SYN1e00`/`SYN0002`/`PNP0f13`, board id: 2869) |
| Touchscreen | ELAN (`04f3:2073` via internal USB) |
| Audio | Intel® Sunrise Point-LP HD Audio / Conexant CX20724 (`8086:9d70`, Apple layout 3 or 13) |
| WiFi | Intel® Dual Band Wireless-AC 7265 (`8086:095a` via PCI) |
| Bluetooth | `8087:0a2a` via Intel AC7265 and USB bus |
| Webcam | HP TrueVision Full HD WVA Webcam (`1bcf:2c7d` via USB) |
| SSD | LITEON CV1-8B256 |

Also:

* `8086:9d31` - Intel® Sunrise Point-LP Thermal subsystem

### CPU Architectures (for reference)

(Since many manuals are talking about these.)

* Clarkdale (older)
* Sandy Bridge
* Ivy Bridge
* Haswell
* Broadwell
* **SKYLAKE** <-- YOU ARE HERE!
* Kaby Lake
* Coffee Lake (newer)

What works
----------

* Keyboard (via [VoodooPS2](https://github.com/acidanthera/VoodooPS2))
* Touchpad (via [VoodooRMI](https://github.com/VoodooSMBus/VoodooRMI) with [VoodooSMBus](https://github.com/VoodooSMBus/VoodooSMBus) + [VoodooPS2](https://github.com/acidanthera/VoodooPS2))
* Touchscreen (via [VoodooI2C](https://github.com/VoodooI2C/VoodooI2C) with VoodooI2CHID)
* GPU acceleration
* HDMI output (didn't test sound)
* Sound (incl. microphone)
* Webcam
* WiFi (using experimental [AirportItlwm](https://github.com/OpenIntelWireless/itlwm))
* Bluetooth (can't toggle on/off from macOS, though)
* Sleep

What doesn't work
-----------------

* Battery readout (didn't hotpatch ACPI yet)
* Apple TV+ (DRM?)
* Unlock via Apple Watch (see AirportItlwm)
* Audio in OpenCore (no boot chime)


Helpful URLs
------------

### Issues

* https://github.com/syscl/XPS9350-macOS/issues/25
* https://www.reddit.com/r/hackintosh/comments/ee9wwi/need_help_with_hp_spectre_x360_ae052nr/
* https://www.reddit.com/r/hackintosh/comments/adovqx/iso_successful_build_hp_spectre_x360_skylake/


### How Tos

* https://www.vice.com/en_us/article/8xznw4/how-to-make-a-hackintosh-laptop
* https://dortania.github.io/ <--- **BEST EVER!!**


### Tools

* https://github.com/corpnewt/gibMacOS
