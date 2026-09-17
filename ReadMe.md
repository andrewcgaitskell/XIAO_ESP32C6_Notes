# XIAO ESP32C6

## Bootloader Mode

Orientation USB C Up and facing you

BOOT Right

RESET Left

press and hold the BOOT and then press RESET
release BOOT

## Force Native Boot Mode on Plug-in

If a previously flashed sketch crashed the chip's internal USB configuration, it might refuse to mount as a serial device.

Disconnect the USB cable.Press and hold the BOOT button down.

Plug the USB cable back in while continuing to hold the BOOT button.Release the BOOT button and run ls /dev/cu.* again.
