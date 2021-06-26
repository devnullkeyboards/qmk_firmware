# bm68rgb

![marklee](https://i.imgur.com/uuYP8OIl.jpeg)

A 65% hotswap in switch RGB keyboard based off of BM65 from KPRepublic.

* Keyboard Maintainer: [devnullkeyboards](https://github.com/devnullkeyboards)
* Hardware Supported: BM68 RGB
* Hardware Availability: [KP Republic](https://kprepublic.com/products/bm65rgb-bm65-rgb-65-hot-swappable-custom-mechanical-keyboard-pcb-programmed-qmk-via-firmware-full-rgb-switch-underglow-type-c)

Make example for this keyboard (after setting up your build environment):

    make devnullkeyboards/marklee:default

And for VIA

    make devnullkeyboards/marklee:via

Flashing example for this keyboard:

    make devnullkeyboards/marklee:default:flash

And for VIA flashing

    make devnullkeyboards/marklee:via:flash

To reset the board into bootloader mode, do one of the following:

* Short the two-pad footprint to the left of the spacebar switch while the board is plugged in
* Hold the Esc key while connecting the USB cable (also erases persistent settings)

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).
