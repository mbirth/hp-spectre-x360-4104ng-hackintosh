HP Spectre x360 13-4104ng Hackintosh
====================================

Specs
-----

|   |  |
| --- | ---|
| CPU | Intel® Core™ i5-6200U (Skylake, 2.3 GHz, up to 2.8 GHz, 3 MB cache, 2 cores) |
| GPU | Intel® HD Graphics 520 |
| RAM | 8 GB DDR3L on-board |
| Display | 13.3" QHD IPS LED-backlit touch screen (2560x1440) |
| Touchpad | HP Control Zone (Synaptics PS/2)|
| Touchscreen | ELAN |
| Audio | HD Audio Conexant CX20724 (Apple layout 3 or 13) |
| WiFi | Intel® Dual Band Wireless-AC 7265 |
| Bluetooth | via Intel AC7265 and USB bus |
| Webcam | HP TrueVision Full HD WVA Webcam |
| SSD | LITEON CV1-8B256 |

### CPU Architectures

* Clarkdale
* Sandy Bridge
* Ivy Bridge
* Haswell
* Broadwell
* **SKYLAKE** <-- YOU ARE HERE!
* Kaby Lake
* Coffee Lake

What works
----------

* Keyboard
* Touchpad
* Touchscreen
* GPU acceleration
* HDMI output (ext. display not recognised if plugged during boot, didn't test sound)
* Sound (incl. microphone)
* Webcam
* WiFi (using experimental [itlwm](https://github.com/OpenIntelWireless/itlwm) and [HeliPort](https://github.com/OpenIntelWireless/HeliPort))
* Bluetooth (can't toggle on/off from macOS, though)
* Sleep

What doesn't work
-----------------

* Battery readout (didn't hotpatch ACPI yet)
* Audio in OpenCore (e.g. no boot chime)


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
