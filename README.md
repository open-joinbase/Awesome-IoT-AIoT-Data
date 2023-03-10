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
- [Platform](#platform)
- [IoT Clouds](#iot-clouds)
- [IIoT Clouds](#iiot-clouds)
- [APIs](#apis)
- [Middleware](#middleware)

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

## Platform

|Name|Status|Introduction|
|------|------|------|
|[JoinBase](https://github.com/open-joinbase)|active|JoinBase is the single binary AIoT-first data-service platform. For Free. 25 million sustained 40B messages per second. Crafted engine is pushing the power of modern hardware to the limit. Interfaces with HTTP, WebSocket, MQTT, PostgreSQL and their TLS variants are available in the highest performance forms.|
|[ActorCloud](https://github.com/actorcloud/ActorCloud)|inactive|ActorCloud is an IoT platform that provides one-stop platform services for enterprises with low-power IoT networks. It provides multiple protocol access, message flow management, data parsing and data processing capabilities for devices on a secure and reliable basis.|
|[Astarte](https://github.com/astarte-platform/astarte)|active|Astarte is an Open Source IoT platform written in Elixir. It is a turnkey solution which packs in everything you need for connecting a device fleet to a set of remote applications. It performs data modeling, automated data reduction, real-time events, and provides you with any feature you might expect in a modern IoT platform. Right now, Linux and ESP32 devices are supported out of the box using the provided SDKs.|
|[DeviceHive](https://github.com/devicehive)|active|IoT Data Platform. Wide range of connectivity options, device management, security and data processing.|
|[embARC Open Software Platform (OSP)](https://github.com/foss-for-synopsys-dwc-arc-processors/embarc_osp)|active|is a software distribution aimed at facilitating the development of embedded systems based on ARCv2 Processors.|
|[GrovePi](https://github.com/DexterInd/GrovePi)|active|is an open source platform for connecting Grove Sensors to the Raspberry Pi.|
|[HiveMQ](https://github.com/hivemq/hivemq-community-edition)|active|is an open source MQTT platform and MQTT broker.|
|[Hologram](https://hologram.io/)|active|Open source, full stack platform with standalone devices and usb plug in. Offers a free developer tier.|
|[IoT.js](https://github.com/Samsung/iotjs)|inactive|Platform for Internet of Things with JavaScript.|
|[Jasper](http://jasperproject.github.io/)|active|Jasper is an open source platform for developing always-on, voice-controlled applications.|
|[KERBEROS.IO Web](https://github.com/kerberos-io/web)|active|a  GUI to configure the machinery and to view events that were detected by the machinery.|
|[Kitnic](https://github.com/monostable/kitnic)|active|A registry for ready to build open hardware electronics projects.|
|[Lan](https://github.com/phodal/lan)|active|Internet of Things Server Layer with CoAP, WebSocket, MQTT, HTTP|
|[Mainflux](https://github.com/Mainflux/mainflux)|active|Mainflux is an open source and patent-free IoT cloud platform based on microservices.|
|[Mobius](https://github.com/IoTKETI/Mobius)|active|is the open source IoT server platform based on the oneM2M standard.|
|[Mongoose IoT](https://github.com/cesanta/iot)|active|is a full-stack IoT platform including firmware and cloud components available for ESP8266.|
|[Nebula](http://nebula.readthedocs.io)|active|A docker orchestrator designed to manage IoT devices|
|[PharoThings](https://github.com/pharo-iot/PharoThings)|inactive|is a Live programming platform for IoT projects based on Pharo.|
|[PlatformIO](https://github.com/platformio/platformio)|active|PlatformIO is a cross-platform code builder and the missing library manager.|
|[Siemens MindSphere](https://www.siemens.com/global/en/home/products/software/mindsphere.html)|active|Open, cloud-based IoT operating system (uses OPC UA as communication standard) from Siemens which is extensible with services.|
|[ThingEngine](https://github.com/Stanford-Mobisocial-IoT-Lab/thingengine-core)|inactive|An open source platform for IoT rules that you can execute anywhere you want.|
|[Thingsboard](https://github.com/thingsboard/thingsboard)|active|Open-source IoT Platform - Device management, data collection, processing and visualization.|
|[Toit](https://toit.io/)|active|The Toit platform combines the functionality of serving your devices in a robust, resilient way, and letting you have control over your devices and your data, as well as ready-to-use over-the-air firmware and application updates on your network-connected embedded devices.|
|[United Manufacturing Hub](https://github.com/united-manufacturing-hub/united-manufacturing-hub)|active|The Open-Source Manufacturing App Platform (combines various open source solutions and packages them in a Helm chart, for example nodered, VerneMQ and timescaleDB)|

## IoT Clouds

|Name|Status|Introduction|
|------|------|------|
|[JoinBase](https://github.com/open-joinbase)|active|JoinBase is the single binary AIoT-first data-service platform. For Free. 25 million sustained 40B messages per second. Crafted engine is pushing the power of modern hardware to the limit. Interfaces with HTTP, WebSocket, MQTT, PostgreSQL and their TLS variants are available in the highest performance forms.|
|[Agile IoT Platform](https://www.aylanetworks.com/products/iot-platform)|active|Ayla Networks IoT Platform (with cloud services).|
|[AlibabaCloud](https://intl.aliyun.com/solutions/IoT)|active|"A cloud computing solution"|
|[ARM Pelion](https://www.pelion.com/)|active|"Arm Pelion IoT Platform including Connectivity, Device and Data management service"|
|[Artik Cloud](https://artik.cloud/)|active|Samsung cloud for the IoT.|
|[AWS IoT](https://aws.amazon.com/iot/)|active|Amazon cloud for the IoT.|
|[Azure IoT Hub](https://azure.microsoft.com/en-us/services/iot-hub/)|active|Microsoft cloud for the IoT.|
|[Bosch IoT Cloud](https://www.bosch-si.com/products/bosch-iot-suite/iot-cloud/bosch-iot-cloud-2.html)|active|Highly scalable cloud infrastructure based on Cloud Foundry.|
|[CloudPlugs IoT](https://cloudplugs.com/)|active|"An end-to-end Fog Computing Platform for IoT."|
|[Exosite murano](https://exosite.com/platform/)|active|IoT platform by Exosite.|
|[Google Cloud IoT](https://cloud.google.com/solutions/iot/)|active|Google Cloud Platform IoT solutions.|
|[Huawei Cloud IoTDA](https://www.huaweicloud.com/product/iothub.html)|active|Huawei cloud for the IoT.|
|[IBM Watson](http://www.ibm.com/watson/)|active|IBM cloud for the IoT.|
|[Oracle IoT Cloud](https://cloud.oracle.com/iot)|active|ORACLE Cloud for the Internet of Things.|
|[Rightech IoT Cloud](https://app.rightech.io)|active|IoT platform.|
|[Salesforce IoT Cloud](http://www.salesforce.com/iot-cloud/)|active|Salesforce cloud for the Internet of Things.|
|[SAP HANA](https://www.sap.com/products/iot-platform-cloud.html)|active|SAP cloud for the Internet of Things.|
|[Siemens MindSphere](http://www.siemens.com/global/en/home/company/topic-areas/digitalization/mindsphere.html)|active|Open IoT ecosystem as PaaS.|
|[Xively IoT Cloud](https://www.xively.com/)|active|IoT platform.|
|[Yaler](https://yaler.net/)|active|"Relay infrastructure for secure access to embedded systems".|
|[Zatar](http://www.zatar.com/)|active|"Zatar is the first ARMmbed standards-based IoT cloud service".|
|[EMQX Cloud](https://www.emqx.com/en/cloud)|active|Fully managed MQTT service for IoT. Connect your IoT devices to any cloud without the burden of maintaining infrastructure.|
|[IoTSharp](https://github.com/IoTSharp/IoTSharp)|active|IoTSharp is an open-source IoT platform.|

## IIoT Clouds

|Name|Status|Introduction|
|------|------|------|
|[DataXChange](https://www.scytec.com/)|active|Cloud manufacturing.|
|[deviceWISE for Factory](http://www.telit.com/solutions/industries/smart-manufacturing/)|active|Telit IIoT cloud.|
|[Predix](https://www.predix.com/)|active|Industrial IoT cloud (by General Electric).|
|[Thingworx](https://www.thingworx.com/platforms/industrial-connectivity/)|active|Industrial IoT cloud.|
|[Voice of the Machine](http://www.parker.com/portal/site/PARKER/menuitem.17c8315d31f057bc86a6c3544256d1ca/?vgnextoid=244744e25684b510VgnVCM100000e6651dacRCRD&vgnextchannel=9f45216358d55510VgnVCM100000e6651dacRCRD&vgnextfmt=)|active|Industrial IoT cloud (by Parker Hannifin, based on Exosite).|

## APIs

|Name|Status|Introduction|
|------|------|------|
|[OGC SensorThings API](https://github.com/opengeospatial/sensorthings)|active|The OGC SensorThings API is an OGC standard specification for providing an open and unified way to interconnect IoT devices, data, and applications over the Web|


## Middleware

|Name|Status|Introduction|
|------|------|------|
|[Kaa](https://github.com/kaaproject/kaa)|active|Kaa open-source middleware platform for building, managing, and integrating connected products with the Internet of Everything.|
|[Kuzzle](https://github.com/kuzzleio/kuzzle)|active|An open-source backend with advanced features like real-time pub/sub or geofencing and a multiprotocol interface that supports MQTT, LoRaWAN and more. [(Website)](https://kuzzle.io/solutions/technologies/iot-backend/)|
|[Meact](https://github.com/bkupidura/meact)|inactive|task is to get metric from external stuff, write it to  and perform various action.|
|[OpenIoT](https://github.com/OpenIotOrg/openiot)|active|The OpenIoT middleware infrastructure will support flexible configuration and deployment of algorithms for collection|
|[SiteWhere](https://github.com/sitewhere/sitewhere)|inactive|SiteWhere open-source IoT platform for device connectivity & management, data persistence, processing, integration, and analytics -- both in cloud and on-premise.|
|[t6](https://github.com/mathcoll/t6)|active|Data-first IoT platform to connect physical Objects with time-series DB and perform Data Analysis.|


## Toolkits Include Non-OS

Layered architecture of JTAG interface and TAP support

|Name|Status|Introduction|
|------|------|------|
|[iot-adk-addonkit](https://github.com/ms-iot/iot-adk-addonkit)|active|Contains command line scripts for package creation and image creation process and samples for iot products based on RPi2/MBM.|
|[macchina.io](https://github.com/macchina-io/macchina.io)|active|An open-source toolkit for building embedded IoT applications that connect sensors, devices and cloud services.|
|[pyOCD](https://github.com/mbedmicro/pyOCD)|active|Open source python library for programming and debugging ARM Cortex-M microcontrollers using CMSIS-DAP.|
|[Renode](https://github.com/renode/renode)|active|a virtual development tool for multinode embedded networks.|
