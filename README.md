# BeagleV-Fire
BeagleV®-Fire is a revolutionary SBC powered by the Microchip’s PolarFire® MPFS025T FCVG484E 5x core RISC-V System on Chip (SoC) with FPGA fabric. BeagleV®-Fire opens up new horizons for developers, tinkerers, and the open-source community to explore the vast potential of RISC-V architecture and FPGA technology. It has the same P8 & P9 cape header pins as BeagleBone Black allowing you to stack your favourite BeagleBone cape on top to expand it’s capability. Built around the powerful and energy-efficient RISC-V instruction set architecture (ISA) along with its versatile FPGA fabric, BeagleV®-Fire SBC offers unparalleled opportunities for developers, hobbyists, and researchers to explore and experiment with RISC-V technology.

## Links

* Terms and conditions: https://docs.beagleboard.org/latest/boards/terms-and-conditions.html
* Documentation: https://docs.beagleboard.org/latest/boards/beaglev/fire
* Design: https://git.beagleboard.org/beaglev-fire/beaglev-fire
* Support: https://forum.beagleboard.org/tags/c/beaglev/15/fire
* Repair: https://www.beagleboard.org/rma
* Purchase: https://beaglev-fire.org

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
* M.2 connector and with daughterboard reference designs
  * 2.4GHz WiFi/Bluetooth using ATWILC3000 and Sub-GHz transceiver using AT86RF212B
  * USB 3 Type-A with SuperSpeed (repurpose PCIe SERDES)
* TagConnect compatible JTAG header footprint
* USB Type-C with SuperSpeed/PCIe, able to provide power
* CSI / Low-speed flexible flat cable (FFC) expansion connector
* ~CANOpen 10-pin multipole connector, reserved signals brought to SoC~
* [Support for HDMI framer board through Cape headers](https://wiki.seeedstudio.com/BeagleBone_Green_HDMI_Cape/)
* Additional power connector
* [SYZYGY high-speed expansion connector](https://syzygyfpga.io/)
