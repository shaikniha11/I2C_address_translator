I2C_address_translator:
This FPGA-based I²C Address Translator enables dynamic remapping of a device’s I²C address, allowing identical-address devices to share a bus. It functions as a slave to the master and master to the device, ensuring reliable bidirectional communication with full compliance to standard 100 kHz and 400 kHz I²C timing.

Overview:
This project implements an "FPGA-based I²C Address Translator" that allows devices with identical default I²C addresses to coexist on the same bus. The translator acts as:
- An I²C Slave to the system master.
- An I²C Master to the target device.

Features:
- Dynamic I²C address remapping.
- Supports 100 kHz and 400 kHz standard timing.
- FSM-based logic design with shift registers and counters.
- Verified with simulation and waveform output.

Tools Used:
- Icarus Verilog 
- GTKWave for waveform analysis

Author:
SHAIK NIHASUHANI — FPGA and Digital Design Enthusiast

