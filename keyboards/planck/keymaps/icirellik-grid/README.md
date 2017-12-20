# iciRellik's Keymap

## Build

Install the required dependencies.

Ubuntu

```sh
$ sudo apt-get update
$ sudo apt-get install gcc unzip wget zip gcc-avr binutils-avr avr-libc dfu-programmer dfu-util gcc-arm-none-eabi binutils-arm-none-eabi libnewlib-arm-none-eabi
```


Compile the keymap and then install it.

```sh
$ make plankck/rev4:icirellik-grid

# Set your keyboard to program mode before running thtis command.
$ make planck/rev4:icriellik-grid:dfu
```
