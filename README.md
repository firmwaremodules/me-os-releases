# Measurement{Earth} Operating System

Measurement{Earth} is a project developing environmental sensing solutions using wireless technologies and low-powered and low-cost STM32 MCUs at the core.  

ME-OS is a unique full-featured operating system designed for such solutions.  It includes the [STM32 Secure Patching Bootloader](https://github.com/firmwaremodules/stm32-secure-patching-bootloader) to allow in-application firmware updates through any packetized delivery framework like ethernet, wifi, bluetooth, lora, lorawan, CAN, modbus, UART and so on, or using the bootloader's built-in UART/YMODEM or USB flash updater.

ME-OS is a true tickless low-power OS that leverages the RTC as its timebase, allowing all of the clocks and components to be turned off in between events for the ultimate deep sleep.

ME-OS is used in projects that include the Measurement{Earth} Trusted Sensor Platform, an environmental sensing solution that uses blockchain for the data authentication and distribution system.

ME-OS firmware releases are distributed as patches, and consequently work only with products already hosting a licensed installation of the OS.

## Public Firmware Releases

ME-OS is currently not distributed independently from the application.  Please see our [Trusted Sensor Platform releases repository](https://github.com/firmwaremodules/me-tsp-releases) for firmware for those devices.


