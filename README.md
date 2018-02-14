### Nitrokey Storage Developer Hardware ###

In this branch, you can find the layout files for the Developer Versions of the Nitrokey Storage. It contains two versions of the PCB:

- Developer Version 2.1: Makes most of the MCUs pins accessible. If you want access to the GPIO, UART and other peripherals, this is for you.
- Developer Version 2.7: Comes in a form factor similar to the Nitrokey Storage, but makes the JTAG pins of the MCU accessible. Use this if you only need JTAG programming/debugging. A quick introduction on how to set up a debugger can be found in the [Nitrokey Storage Firmware Repository][debugger]

All design files work with [Design Spark PCB][designspark]

[designspark]: https://www.rs-online.com/designspark/pcb-software
[debugger]: https://github.com/Nitrokey/nitrokey-storage-firmware
