Awesome IoT and AIoT Data![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)
===

A curated list of active IoT and AIoT data projects. Everyone can contribute here!

The rules for the status in the list are as follows：
- The status of the project is "active", if there is at least one commit in that project within the past one year;
- The status of the project is "inactive", if there is no commit in that project within the past one year;
- The project item will be removed if there is no commit in that project within the past three year;

ToC
---

- [Framework](#framework)
- [Library](#library)
   - [SDK](#sdk)
   - [Arduino](#arduino)
   - [Low Level](#low-level)
- [App](#app)
- [Storage](#storage)
- [Security](#security)
- [OS](#os)
   - [Android Things](#android-things)
- [Voice Controller](#voice-controller)
## Framework

|Name|Status|Introduction|
|------|------|------|
|[JoinBase](https://github.com/open-joinbase)|active|JoinBase is the single binary AIoT-first data-service platform. For Free. 25 million sustained 40B messages per second. Crafted engine is pushing the power of modern hardware to the limit. Interfaces with HTTP, WebSocket, MQTT, PostgreSQL and their TLS variants are available in the highest performance forms.|
|[.NET Core IoT](https://github.com/dotnet/iot)|active|A set of libraries to interact with sensors, displays and input devices from .NET Core framework.This libraries allows to work with the GPIO port for various boards like Raspberry Pi and Hummingboard and contains a growing set of community-maintained device bindings for IoT components.|
|[AREG SDK](https://github.com/aregtech/areg-sdk)|active|AREG SDK is a developer-friendly, an interface-centric real-time asynchronous communication engine to enable distributed- and [mist-computing](https://csrc.nist.gov/publications/detail/sp/500-325/final), where connected Things interact and provide services, as if they act like thin distributed servers.|
|[ESP-IDF](https://github.com/espressif/esp-idf)|active|The official framework from Espressif to build Wi-Fi, BLE, and BT apps with ESP32.|
|[Freedomotic](https://github.com/freedomotic/freedomotic)|active|is an open source, flexible, secure Internet of Things (IoT)|
|[GoBot](https://github.com/hybridgroup/gobot)|active|Golang framework for robotics, physical computing, and the Internet of Things.|
|[johnny-five](https://github.com/rwaldron/johnny-five)|active|JavaScript Robotics and IoT programming framework, developed at Bocoup, Firmata Protocol.|
|[Kura](https://github.com/eclipse/kura)|active|an open-source framework for development of IoT applications|
|[Lightweight MQTT Machine Network](http://lwmqn.github.io/)|inactive|LWMQN is a machine network framework with MQTT. See also: IPSO Alliance [Technical Archive](http://www.ipso-alliance.org/ipso-community/resources/technical-archive/).|
|[Liota](https://github.com/vmware/liota)|inactive|is an open source offering for IoT solution developers and resides primarily on IoT gateways.|
|[OpenDevice](https://github.com/OpenDevice/OpenDevice)|active|Open IoT (Internet Of Things) Platform and Framework.|
|[rpi-gpio.js](https://github.com/JamesBarwell/rpi-gpio.js)|inactive|Control Raspberry Pi GPIO pins with node.js.|
|[Serverless](https://github.com/serverless/serverless)|active|Serverless is the application framework for building web, mobile and IoT applications exclusively on Amazon Web Services' Lambda and API Gateway.|
|[Simgrid](https://github.com/simgrid/simgrid)|active|is a scientific instrument to study the behavior of large-scale distributed systems such as Grids, Clouds, HPC or P2P systems.
|[Sming](https://github.com/SmingHub/Sming)|active|Sming is an asynchronous C/C++ framework with superb performance and multiple network features. Sming is open source and is tailored towards embedded devices.|
|[Thingsboard IoT Gateway](https://github.com/thingsboard/thingsboard-gateway)|active|open-source IoT Gateway - integrates devices connected to legacy and third-party systems with Thingsboard IoT Platform using OPC-UA and MQTT protocols.|

## Library


### SDK

|Name|Status|Introduction|
|------|------|------|
|[AWS IoT Arduino Yún SDK](https://github.com/aws/aws-iot-device-sdk-arduino-yun)|active|for creating customized kernel and Debian based userspace for popular development boards.|
|[Armbian build SDK](https://github.com/armbian/build)|active|for creating customized kernel and Debian based userspace for popular development boards.|
|[ESP8266 Arduino Core](https://github.com/esp8266/Arduino)|active|Arduino core for ESP8266 WiFi chip.|
|[Microsoft Azure IoT SDK](https://github.com/Azure/azure-iot-sdks)|active|SDKs for a variety of languages and platforms that help connect devices to Microsoft Azure IoT services.|

### Arduino

|Name|Status|Introduction|
|------|------|------|
|[ArduinoJson](https://github.com/bblanchon/ArduinoJson)|active|An elegant and efficient JSON library for embedded systems.|
|[PJON](https://github.com/gioblu/PJON)|active|Digital communication framework for Arduino and IOT.|
|[WiringPi](https://github.com/WiringPi/WiringPi)|active|Gordon's Arduino wiring-like WiringPi Library for the Raspberry Pi.|


### Low Level

|Name|Status|Introduction|
|------|------|------|
|[aWOT](https://github.com/lasselukkari/aWOT)|active|Web server library for Arduino, Teensy, ESP8266 and ESP32|
|[btstack](https://github.com/bluekitchen/btstack)|active|Dual-mode Bluetooth stack, with small memory footprint.|
|[CocoaMQTT](https://github.com/emqtt/CocoaMQTT)|active|MQTT for iOS and OS X written with Swift.|
|[fauxmoESP](https://bitbucket.org/xoseperez/fauxmoesp)|inactive|Belkin WeMo emulator library for ESP8266.|
|[inih](https://github.com/benhoyt/inih)|active|is a simple .INI file parser written in C.|
|[Ladon](https://github.com/ory-am/ladon)|active|is a library written in Go for access control policies, similar to Role Based Access Control or Access Control Lists.|
|[libui](https://github.com/andlabs/libui)|inactive|Simple and portable (but not inflexible) GUI library in C that uses the native GUI technologies of each platform it supports.|
|[LK](https://github.com/littlekernel/lk)|active|The LK embedded kernel. An SMP-aware kernel designed for small systems.|
|[matrixssl](https://github.com/matrixssl/matrixssl)|active|is an embedded SSL and TLS implementation designed for small footprint IoT devices requiring low overhead per connection.|
|[MCUBoot](https://github.com/runtimeco/mcuboot)|active|is a secure bootloader for 32-bit MCUs.|
|[nexmon](https://github.com/seemoo-lab/nexmon)|active|is our C-based firmware patching framework for Broadcom/Cypress WiFi chips.|
|[Pelion Device Management Client](https://github.com/ARMmbed/mbed-cloud-client)|active|a library that connects devices to Pelion Device Management service and to Mbed-enabled cloud services from our partners.|
|[simbody](https://github.com/simbody/simbody)|active|High-performance C++ multibody dynamics/physics library for simulating articulated biomechanical and mechanical systems like vehicles, robots, and the human skeleton.|
|[SPIFFS](https://github.com/pellepl/spiffs)|active|Wear-leveled SPI flash file system for embedded devices.|
|[SwiftyGPIO](https://github.com/uraimo/SwiftyGPIO)|inactive|a Swift library to interact with Linux GPIO/SPI on ARM.|
|[XiPKI](https://github.com/xipki/xipki)|active|eXtensible sImple Public Key Infrastructure consists of CA and OCSP responder.|

## App

|Name|Status|Introduction|
|------|------|------|
|[MQTTX](https://github.com/emqx/MQTTX)|active|MQTTX is a cross-platform MQTT desktop client open sourced by EMQ, which supports macOS, Linux, and Windows. It allows users to quickly and easily test MQTT / MQTTS connections, publish and subscribe to MQTT messages.|
|[PhoneGap](https://github.com/chariotsolutions/phonegap-nfc)|inactive|PhoneGap NFC Plugin|
|[PWAify](https://github.com/vladikoff/PWAify)|inactive|Experimental project to convert your PWA (Progressive Web App) into a cross-platform Electron app. Brings PWAs to your desktop.|

## Storage

|Name|Status|Introduction|
|------|------|------|
|[HStreamDB](https://github.com/hstreamdb/hstream)|active|The streaming database built for IoT data storage and real-time processing.|


## Security

|Name|Status|Introduction|
|------|------|------|
|[Scanners-Box](https://github.com/We5ter/Scanners-Box)|active|the toolbox of open source scanners.|

## OS

|Name|Status|Introduction|
|------|------|------|
|[Mynewt](https://github.com/apache/mynewt-core)|active|is an open-source operating system for tiny embedded devices. Its goal is to make it easy to develop applications for microcontroller environments where power and cost are driving factors.|
|[Amazon FreeRTOS](https://github.com/aws/amazon-freertos)|active|is an operating system for microcontrollers that makes small, low-power edge devices easy to program, deploy, secure, connect, and manage.|
|[ARM mbed](https://github.com/mbedmicro/mbed)|active|The ARM® mbed™ IoT Device Platform provides the operating system, cloud services, tools and developer ecosystem to make the creation and deployment of commercial, standards-based IoT solutions possible at scale.|
|[Armbian](https://www.armbian.com)|active|Debian based Docker enabled lightweight Linux for popular development boards. Optimised for embedded usage.|
|[Brillo](https://developers.google.com/brillo/)|active|Brillo extends the Android platform to all your connected devices.|
|[Huawei LiteOS](https://github.com/LITEOS/LiteOS_Kernel)|inactive|Huawei LiteOS Kernel.|
|[Hypriot](https://github.com/hypriot/image-builder-rpi)|active|HypriotOS for the Raspberry Pi is a Debian-based Container OS optimized for Docker.|
|[Lua-RTOS-ESP32](https://github.com/whitecatboard/Lua-RTOS-ESP32)|active|is a real-time operating system designed to run on embedded systems, with minimal requirements of FLASH and RAM memory.|
|[macchina.io](https://github.com/macchina-io/macchina.io)|active|An open-source toolkit for building embedded IoT applications that connect sensors, devices and cloud services.|
|[NuttX](http://nuttx.org/)|active|is a real-time operating system (RTOS) with an emphasis on standards compliance and small footprint.Scalable from 8-bit to 32-bit microcontroller environments, the primary governing standards in NuttX are Posix and ANSI standards.|
|[OpenWrt](https://github.com/openwrt/openwrt)|active|OpenWrt is described as a Linux distribution for embedded devices.|
|[pikoRT](https://github.com/Piko-RT/pikoRT)|active|A tiny Linux-like real-time kernel optimized for ARM Cortex-M chips.|
|[Raspbian](http://raspbian.org/)|active|Raspbian is a free operating system based on Debian optimized for the Raspberry Pi hardware.|
|[RIOT](https://github.com/RIOT-OS/RIOT)|active|The friendly Operating System for the Internet of Things.|
|[RT-Thread](https://github.com/RT-Thread/rt-thread)|active|RT-Thread is an open source real-time operating system for embedded devices from China.|
|[seL4 Microkernel](https://github.com/seL4/seL4)|active|The world's first operating-system kernel with an end-to-end proof of implementation correctness and security enforcement is available as open source.|
|[TachyOS](https://github.com/fritzprix/TachyOS)|inactive|is the RTOS based on microkernel architecture which includes only minimal components like thread / synchronization, memory management, inter-thread communication while supporting execution context / address space isolation(protection) and extensible modular interface.|
|[TinyAra](https://github.com/Samsung/TinyAra)|active|is a lightweight RTOS-based platform to support low-end IoT devices.|
|[TinyOS](https://github.com/tinyos/tinyos-main)|inactive|designed for low-power wireless devices, such as those used in sensor networks, ubiquitous computing, personal area networks, smart buildings, and smart meters.|
|[Tock OS](https://github.com/helena-project/tock)|active|is an operating system designed for running multiple concurrent, mutually distrustful applications on Cortex-M based embedded platforms.|
|[Zephyr](https://github.com/zephyrproject-rtos/zephyr)|active|is a small, scalable real-time operating system for use on resource-constrained systems supporting multiple architectures.|


### Android Things

|Name|Status|Introduction|
|------|------|------|
|[Android Things user-space drivers](https://github.com/androidthings/contrib-drivers)|inactive|Sample peripheral drivers for Android Things.|

## Voice Controller

|Name|Status|Introduction|
|------|------|------|
|[flask-ask](https://github.com/johnwheeler/flask-ask)|active|is a Flask extension that makes building Alexa skills for the Amazon Echo easier and much more fun.|

