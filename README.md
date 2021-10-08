# BeagleV-Fire
Placeholder for work on a Polarfire SoC based RISC-V BeagleBone compatible board

## Goals
* Provide a platform for developing fully open-source SoCs
* Provide solution for low-latency control, such as manufacturing machines
* Long-term availability for education

## Initial features in rank order of priority
* Microchip MPFS025T-FCVG484E RISC-V based Polarfire SoC with 25k logic elements
* BeagleBone AI compatible mechanical footprint, expansion headers, serial header, buttons, LEDs and microSD slot
* 2GB LPDDR4
* 16GB eMMC
* Gigabit Ethernet
* M.2 connector for 2.4GHz WiFi/Bluetooth using ATWILC3000 and Sub-GHz transceiver using AT86RF212B (board to be developed)
* TagConnect compatible JTAG header footprint
* USB Type-C with SuperSpeed/PCIe, able to provide power
* ~USB Type-A with SuperSpeed~
* CSI / Low-speed flexible flat cable (FFC) expansion connector
* ~CANOpen 10-pin multipole connector, reserved signals brought to SoC~
* [Support for HDMI framer board through Cape headers](https://wiki.seeedstudio.com/BeagleBone_Green_HDMI_Cape/)
* Additional power connector
* [SYZYGY high-speed expansion connector](https://syzygyfpga.io/)
