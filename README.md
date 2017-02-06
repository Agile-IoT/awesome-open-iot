# awesome-open-iot [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome open source IoT frameworks, libraries and software.

Note that the list only features components we think are particularly relevant for IoT (e.g they are appropriate for use in embedded IoT devices, deal with the specific constraints of IoT communication networks, etc.). The reader will want to refer to the [Awesome](https://github.com/sindresorhus/awesome) catalog for more references in his/her programming language or technical field of choice.

- [Awesome Open IoT](#awesome-open-iot)
  * [Connectivity](#connectivity)
    + [Bluetooth 4.0, Bluetooth Smart (BLE)](#bluetooth-40-bluetooth-smart-ble)
    + [enOcean](#enocean)
    + [KNX](#knx)
    + [LoRa / LoRaWAN](#lora--lorawan)
    + [NFC](#nfc)
    + [RS-232 / Serial](#rs-232--serial)
    + [RS-485](#rs-485)
  * [Data Encoding](#data-encoding)
    + [CBOR](#cbor)
    + [FlatBuffers](#flatbuffers)
    + [Protocol Buffers](#protocol-buffers)
  * [Data Visualization](#data-visualization)
  * [Device Discovery](#device-discovery)
    + [mDNS / Bonjour](#mdns--bonjour)
    + [uPNP](#upnp)
  * [Gateway](#gateway)
  * [Home Automation](#home-automation)
  * [Messaging](#messaging)
    + [CoAP](#coap)
    + [Modbus](#modbus)
    + [MQTT](#mqtt)
    + [MQTT-SN](#mqtt-sn)
    + [OPC-UA](#opc-ua)
  * [Operating Systems](#operating-systems)
  * [Remote Management](#remote-management)
    + [LWM2M](#lwm2m)
    + [OMA-DM](#oma-dm)
    + [SNMP](#snmp)
    + [TR-069](#tr-069)
  * [Robotics and Physical computing](#robotics-and-physical-computing)
  * [Security](#security)
    + [DNS-SEC](#dns-sec)
    + [DTLS](#dtls)
    + [TLS](#tls)
  * [Workflow management](#workflow-management)
- [Contributing](#contributing)

## Connectivity

### Bluetooth 4.0, Bluetooth Smart (BLE)

|                                                                                     Name                                                                                     |                            Description                             | License | Language |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------|---------|----------|
| [bluez](http://www.bluez.org/)                                                                                                                                               | Official Linux Bluetooth protocol stack                            | GPL     | C        |
| [Gatt](https://github.com/paypal/gatt) <br>  [![GitHub stars](https://img.shields.io/github/stars/paypal/gatt.svg?style=social&label=Star&maxAge=2592000)]()                 | Gatt is a Go package for building Bluetooth Low Energy peripherals | BSD-3   | Go       |
| [noble](https://github.com/sandeepmistry/noble) <br> [![GitHub stars](https://img.shields.io/github/stars/sandeepmistry/noble.svg?style=social&label=Star&maxAge=2592000)]() | A Node.js BLE (Bluetooth Low Energy) central module                | MIT     | Node.js  |


### enOcean

|                                                                                                                   Name                                                                                                                   |                          Description                           | License | Language |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------|---------|----------|
| [EnJ](https://github.com/dog-gateway/enj-library) <br> [![GitHub stars](https://img.shields.io/github/stars/dog-gateway/enj-library.svg?style=social&label=Star&maxAge=2592000)]()                                                       | EnJ: EnOcean Java library                                      | ASL     | Java     |
| [Python EnOcean](https://github.com/kipe/enocean) <br> [![GitHub stars](https://img.shields.io/github/stars/kipe/enocean.svg?style=social&label=Star&maxAge=2592000)]()                                                                  | A Python library for reading and controlling EnOcean devices   | MIT     | Python   |
| [serialport-enocean-parser](https://github.com/RafaelKa/node-serialport-enocean-parser) <br> [![GitHub stars](https://img.shields.io/github/stars/RafaelKa/node-serialport-enocean-parser.svg?style=social&label=Star&maxAge=2592000)]() | An EnOcean Serial Protocol 3 (ESP3) parser for node-serialport | WTFPL   | Node.js  |

### KNX

TBC

### LoRa / LoRaWAN

|                                                                                                   Name                                                                                                   |                                                                                       Description                                                                                        | License | Language |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------|----------|
| [LoRa packet forwarder](https://github.com/Lora-net/packet_forwarder) <br> [![GitHub stars](https://img.shields.io/github/stars/Lora-net/packet_forwarder.svg?style=social&label=Star&maxAge=2592000)]() | A program running on the host of a Lora Gateway that forward RF packets receive by the concentrator to a server through a IP/UDP link, and emits RF packets that are sent by the server. | BSD-3   | C        |
| [The Things Network](https://github.com/TheThingsNetwork/ttn) <br> [![GitHub stars](https://img.shields.io/github/stars/TheThingsNetwork/ttn.svg?style=social&label=Star&maxAge=2592000)]()              | A complete LoRaWAN network stack (router, broker, message handler)                                                                                                                       | MIT     | Go       |

### NFC

|                                                                                    Name                                                                                   |                                  Description                                  | License | Language |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------|---------|----------|
| [libnfc](https://github.com/nfc-tools/libnfc)   <br> [![GitHub stars](https://img.shields.io/github/stars/nfc-tools/libnfc.svg?style=social&label=Star&maxAge=2592000)]() | libnfc is a library which allows userspace application access to NFC devices. | LGPL v3 | C        |
| [Go NFC](https://github.com/fuzxxl/nfc)         <br> [![GitHub stars](https://img.shields.io/github/stars/fuzxxl/nfc.svg?style=social&label=Star&maxAge=2592000)]()       | Go bindings for libnfc                                                        | LGPL v3 | Go       |
| [Node NFC](https://github.com/camme/node-nfc)   <br> [![GitHub stars](https://img.shields.io/github/stars/camme/node-nfc.svg?style=social&label=Star&maxAge=2592000)]()   | Node.js bindings for libnfc                                                   | MIT     | Node.js  |
| [Java NFC](https://github.com/grundid/nfctools) <br> [![GitHub stars](https://img.shields.io/github/stars/grundid/nfctools.svg?style=social&label=Star&maxAge=2592000)]() | nfctools library for Java                                                     | ASL     | Java     |

### RS-232 / Serial

|                                                                                                  Name                                                                                                 |                                                  Description                                                   |          License           | Language |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------|----------------------------|----------|
| [Java Simple Serial Connector](https://github.com/Fazecast/jSerialComm) <br> [![GitHub stars](https://img.shields.io/github/stars/Fazecast/jSerialComm.svg?style=social&label=Star&maxAge=2592000)]() | Platform-independent serial port access for Java                                                               | LGPL                       | Java     |
| [rxtx](https://github.com/rxtx/rxtx) <br> [![GitHub stars](https://img.shields.io/github/stars/rxtx/rxtx.svg?style=social&label=Star&maxAge=2592000)]()                                               | A Java cross platform wrapper library for the serial port                                                      | LGPL                       | Java/C   |
| [OpenJDK Device/IO](http://openjdk.java.net/projects/dio/)                                                                                                                                            | The Device I/O Project provides a Java-level API for accessing generic device peripherals on embedded devices. | GPL w/ classpath exception | Java/C   |

### RS-485

TBC

## Data Encoding

This section focuses on data encoding formats that are particularly appropriate for IoT scenarios (i.e bandwidth or battery efficient, small memory footprint, …)

### CBOR

|                                                                                  Name                                                                                 |                                               Description                                                | License | Language |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------|---------|----------|
| [TinyCBOR](https://github.com/01org/tinycbor) <br> [![GitHub stars](https://img.shields.io/github/stars/01org/tinycbor.svg?style=social&label=Star&maxAge=2592000)]() | TinyCBOR is Intel's industrial strength C/C++ implementation of CBOR, as used in the IoTivity framework. | MIT     | C        |

More at: http://cbor.io/impls.html

### FlatBuffers

|                                                                                                Name                                                                                                |                                                  Description                                                  | License |                    Language                   |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------|---------|-----------------------------------------------|
| [Offical libraries from Google](https://github.com/google/flatbuffers) <br> [![GitHub stars](https://img.shields.io/github/stars/google/flatbuffers.svg?style=social&label=Star&maxAge=2592000)]() | FlatBuffers is an efficient cross platform serialization library for games and other memory constrained apps. | ASLv2   | C++, C#, C, Go, Java, JavaScript, PHP, Python |

### Protocol Buffers

|                                                                                             Name                                                                                             |                                                                             Description                                                                              | License |                         Language                         |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------|----------------------------------------------------------|
| [Offical libraries from Google](https://github.com/google/protobuf) <br> [![GitHub stars](https://img.shields.io/github/stars/google/protobuf.svg?style=social&label=Star&maxAge=2592000)]() | Protocol Buffers (a.k.a., protobuf) are Google's language-neutral, platform-neutral, extensible mechanism for serializing structured data.                           | BSD-3   | C++, Java, Python, Objective-C, C#, JavaScript, Ruby, Go |
| [nanopb](https://github.com/nanopb/nanopb) <br> [![GitHub stars](https://img.shields.io/github/stars/nanopb/nanopb.svg?style=social&label=Star&maxAge=2592000)]()                            | Nanopb is a small code-size Protocol Buffers implementation in ansi C. It is especially suitable for use in microcontrollers, but fits any memory restricted system. | BSD-3   | C                                                        |
|                                                                                                                                                                                              |                                                                                                                                                                      |         |                                                          |

## Data Visualization

See [awesome-dataviz](https://github.com/fasouto/awesome-dataviz).

## Device Discovery

### mDNS / Bonjour

|                                                                                    Name                                                                                    |                              Description                              | License | Language |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------|---------|----------|
| [mdns](https://github.com/hashicorp/mdns) <br> [![GitHub stars](https://img.shields.io/github/stars/hashicorp/mdns.svg?style=social&label=Star&maxAge=2592000)]()          | Simple mDNS client/server library in Golang                           | MIT     | Go       |
| [bonjour](https://github.com/oleksandr/bonjour) <br> [![GitHub stars](https://img.shields.io/github/stars/oleksandr/bonjour.svg?style=social&label=Star&maxAge=2592000)]() | mDNS/DNS-SD (also known as Apple Bonjour) library for Go (in pure Go) | MIT     | Go       |
| [node_mdns](http://agnat.github.io/node_mdns) <br> [![GitHub stars](https://img.shields.io/github/stars/agnat/node_mdns.svg?style=social&label=Star&maxAge=2592000)]()     | mDNS/zeroconf/bonjour service discovery add-on for Node.js            | MIT     | Node.js  |
| [mdnsjava](https://github.com/posicks/mdnsjava) <br> [![GitHub stars](https://img.shields.io/github/stars/posicks/mdnsjava.svg?style=social&label=Star&maxAge=2592000)]()  | Multicast DNS (mDNS) & DNS-Based Service Discovery (DNS-SD) in Java   | BSD     | Java     |

### uPNP

|                                                                                        Name                                                                                       |              Description               |    License    | Language |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------|---------------|----------|
| [goupnp](https://github.com/huin/goupnp) <br> [![GitHub stars](https://img.shields.io/github/stars/huin/goupnp.svg?style=social&label=Star&maxAge=2592000)]()                     | goupnp is a UPnP client library for Go | BSD-2         | Go       |
| [UpnpServer](https://github.com/oeuillot/upnpserver) <br> [![GitHub stars](https://img.shields.io/github/stars/oeuillot/upnpserver.svg?style=social&label=Star&maxAge=2592000)]() | Fast and light upnp server for Node.js | GPLv2         | Node.js  |
| [Cling](http://4thline.org/projects/cling/)                                                                                                                                       | Java/Android UPnP library and tools    | LGPL/CDDL-1.0 | Java     |

## Gateway

|                                                                              Name                                                                              |                                                          Description                                                           | License | Language |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------|---------|----------|
| [Eclipse Kura](https://eclipse.org/kura) <br> [![GitHub stars](https://img.shields.io/github/stars/eclipse/kura.svg?style=social&label=Star&maxAge=2592000)]() | Eclipse Kura is a Java/OSGi-based framework for IoT gateways                                                                   |         | Java     |
| [OpenWrt](https://openwrt.org/)                                                                                                                                | OpenWrt is an embedded operating system based on the Linux kernel, primarily used on embedded devices to route network traffic | GPLv2   | C, Lua   |
| [UBOS](http://ubos.net) <br> [![GitHub stars](https://img.shields.io/github/stars/uboslinux/ubos-admin.svg?style=social&label=Star&maxAge=2592000)]()          | UBOS is an Arch-derived Linux distro optimized for cost-efficient administration Personal Servers and Indie IoT Devices        | Linux   | many     |

## Home Automation

|                                                                                     Name                                                                                     |                                                                                                                             Description                                                                                                                             | License | Language |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------|----------|
| [Calaos](https://calaos.fr/en/) <br> [![GitHub stars](https://img.shields.io/github/stars/calaos/calaos_base.svg?style=social&label=Star&maxAge=2592000)]()                  | Calaos is a free software project (GPLv3) that lets you control and monitor your home.                                                                                                                                                                              | GPLv3   | C++      |
| [Freedomotic](http://www.freedomotic.com) <br> [![GitHub stars](https://img.shields.io/github/stars/freedomotic/freedomotic.svg?style=social&label=Star&maxAge=2592000)]()                                                                                                                                    | Freedomotic is an open source, flexible, secure Internet of Things (IoT) development framework, useful to build and manage modern smart spaces.                                                                                                                     | GPLv2   | Java     |
| [openHAB](https://github.com/openhab/openhab) <br> [![GitHub stars](https://img.shields.io/github/stars/openhab/openhab.svg?style=social&label=Star&maxAge=2592000)]()       | The open Home Automation Bus (openHAB) project aims at providing a universal integration platform for all things around home automation                                                                                                                             | EPL     | Java     |
| [Eclipse SmartHome](http://eclipse.org/smarthome) <br> [![GitHub stars](https://img.shields.io/github/stars/eclipse/smarthome.svg?style=social&label=Star&maxAge=2592000)]() | The Eclipse SmartHome project is a framework that allows building smart home solutions that have a strong focus on heterogeneous environments. It provides a uniform access to devices and information and to facilitate different kinds of interactions with them. | EPL     | Java     |

## Messaging

### CoAP

|                                                                                      Name                                                                                      |                                        Description                                        | License |   Language  |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------|---------|-------------|
| [Californium](http://www.eclipse.org/californium) <br> [![GitHub stars](https://img.shields.io/github/stars/eclipse/californium.svg?style=social&label=Star&maxAge=2592000)]() | Californium is a Java CoAP implementation for IoT Cloud services.                         | EPL/EDL | Java        |
| [microcoap](https://github.com/1248/microcoap) <br> [![GitHub stars](https://img.shields.io/github/stars/1248/microcoap.svg?style=social&label=Star&maxAge=2592000)]()         | A small CoAP implementation for microcontrollers                                          | MIT     | C (Arduino) |
| [gocoap](https://github.com/dustin/go-coap) <br> [![GitHub stars](https://img.shields.io/github/stars/dustin/go-coap.svg?style=social&label=Star&maxAge=2592000)]()            | Implementation of CoAP in go                                                              | MIT     | Go          |
| [node-coap](https://github.com/mcollina/node-coap) <br> [![GitHub stars](https://img.shields.io/github/stars/mcollina/node-coap.svg?style=social&label=Star&maxAge=2592000)]() | node-coap is a Node.js client and server library for CoAP modelled after the http module. | MIT     | Node.js     |

### Modbus

|                                                                                                     Name                                                                                                     |                                                                                Description                                                                                |  License  | Language |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------|----------|
| [go modbus](https://github.com/goburrow/modbus) <br> [![GitHub stars](https://img.shields.io/github/stars/goburrow/modbus.svg?style=social&label=Star&maxAge=2592000)]()                                     | Fault-tolerant implementation of modbus protocol in Go                                                                                                                    | BSD-3     | Go       |
| [j2mod](https://github.com/steveohara/j2mod)  <br> [![GitHub stars](https://img.shields.io/github/stars/steveohara/j2mod.svg?style=social&label=Star&maxAge=2592000)]()                                                                                                                                                                 | Enhanced Modbus library implemented in the Java programming language                                                                                                      | Apache    | Java     |
| [libmodbus](https://github.com/stephane/libmodbus) <br> [![GitHub stars](https://img.shields.io/github/stars/stephane/libmodbus.svg?style=social&label=Star&maxAge=2592000)]()                               | libmodbus is a free software library to send/receive data with a device which respects the Modbus protocol. This library can use a serial port or an Ethernet connection. | LGPL v2.1 | C        |
| [modbus4j](https://github.com/infiniteautomation/modbus4j) <br> [![GitHub stars](https://img.shields.io/github/stars/infiniteautomation/modbus4j.svg?style=social&label=Star&maxAge=2592000)]()                               | A high-performance and ease-of-use implementation of the Modbus protocol written in Java by Infinite Automation Systems and Serotonin Software. Supports ASCII, RTU, TCP, and UDP transports as slave or master, automatic request partitioning and response data type parsing.| GPL v3 | Java        |
| [node-modbus-stack](https://github.com/TooTallNate/node-modbus-stack) <br> [![GitHub stars](https://img.shields.io/github/stars/TooTallNate/node-modbus-stack.svg?style=social&label=Star&maxAge=2592000)]() | A StreamStack implementation of the MODBUS protocol, for NodeJS.                                                                                                          | MIT       | Node.js  |
| [pymodbus](https://github.com/bashwork/pymodbus) <br> [![GitHub stars](https://img.shields.io/github/stars/bashwork/pymodbus.svg?style=social&label=Star&maxAge=2592000)]()                                  | A full modbus protocol written in Python                                                                                                                                  | BSD       | Python   |

### MQTT

|                                                                                   Name                                                                                  |                                              Description                                              | License |                          Language                          |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|---------|------------------------------------------------------------|
| [Eclipse Paho](http://www.eclipse.org/paho/)                                                                                                                                | The Eclipse Paho project provides open-source client implementations of MQTT                          | EPL/EDL | Java, Python, Javascript, Go, C, .Net (C#), Embedded C/C++ |
| [Moquette](https://github.com/andsel/moquette) <br> [![GitHub stars](https://img.shields.io/github/stars/andsel/moquette.svg?style=social&label=Star&maxAge=2592000)]() | Moquette is a lightweight MQTT broker in Java                                                         | ASLv2   | Java                                                       |
| [MQTT.js](https://github.com/mqttjs/MQTT.js) <br> [![GitHub stars](https://img.shields.io/github/stars/mqttjs/MQTT.js.svg?style=social&label=Star&maxAge=2592000)]()    | MQTT.js is a client library for the MQTT protocol, written in JavaScript for node.js and the browser. | MIT     | Javascript                                                 |
|                                                                                                                                                                         |                                                                                                       |         |                                                            |

### MQTT-SN

|                                                                                       Name                                                                                       |                                     Description                                      | License | Language |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------|---------|----------|
| [mqtt-sn-tools](https://github.com/njh/mqtt-sn-tools) <br> [![GitHub stars](https://img.shields.io/github/stars/njh/mqtt-sn-tools.svg?style=social&label=Star&maxAge=2592000)]() | Command line tools written in C for the MQTT-SN (MQTT for Sensor Networks) protocol. | MIT     | C        |

### OPC-UA

|                                                                                          Name                                                                                         |                                                                      Description                                                                      |            License            | Language |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------|----------|
| [Eclipse Milo](https://eclipse.org/milo) <br> [![GitHub stars](https://img.shields.io/github/stars/eclipse/milo.svg?style=social&label=Star&maxAge=2592000)]()                        | Eclipse Milo provides all the tools necessary to implement OPC Unified Architecture (UA) client and/or server functionality in any JVM-based project. | EPL/EDL                       | Java     |
| [node-opcua](http://node-opcua.github.io/) <br> [![GitHub stars](https://img.shields.io/github/stars/node-opcua/node-opcua.svg?style=social&label=Star&maxAge=2592000)]()             | An implementation of a OPC UA stack fully written in Javascript and Node.js                                                                           | MIT                           | Node.js  |
| [OPC UA .NET](http://opcfoundation.github.io/UA-.NET/) <br> [![GitHub stars](https://img.shields.io/github/stars/OPCFoundation/UA-.NET.svg?style=social&label=Star&maxAge=2592000)]() | The official OPC Foundation OPC UA .NET Stack and sample applications.                                                                                | GPLv2                         | .Net     |
| [open62541](http://open62541.org/) <br> [![GitHub stars](https://img.shields.io/github/stars/open62541/open62541.svg?style=social&label=Star&maxAge=2592000)]()                       | An open source and free C (C99) OPC UA stack licensed                                                                                                 | LGPL+static linking exception | C        |

## Operating Systems

|                                                                                     Name                                                                                     |                                                                                                                   Description                                                                                                                   | License  | Language |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------|----------|
| [Contiki](https://github.com/contiki-os/contiki) <br> [![GitHub stars](https://img.shields.io/github/stars/contiki-os/contiki.svg?style=social&label=Star&maxAge=2592000)]() | Contiki is an open source operating system for the Internet of Things. Contiki connects tiny low-cost, low-power microcontrollers to the Internet.                                                                                              | BSD-3    | C        |
| [FreeRTOS](http://www.freertos.org/)                                                                                                                                         | A cross-platform real-time operating system                                                                                                                                                                                                     | GPL-like | C        |
| [mbed OS](https://www.mbed.com/en/development/software/mbed-os/)                                                                                                             | ARM® mbed™ OS is an open source embedded operating system designed specifically for the "things" in the Internet of Things (IoT). It includes all the features you need to develop a connected product based on an ARM Cortex-M microcontroller | ASLv2    | C/C++    |
| [OpenWrt](https://openwrt.org/)                                                                                                                                              | OpenWrt is an embedded operating system based on the Linux kernel, primarily used on embedded devices to route network traffic                                                                                                                  | GPLv2    | C, Lua   |
| [RIOT-OS](https://github.com/RIOT-OS/RIOT) <br> [![GitHub stars](https://img.shields.io/github/stars/RIOT-OS/RIOT.svg?style=social&label=Star&maxAge=2592000)]()             | RIOT OS is an operating system for Internet of Things (IoT) devices. It is based on a microkernel and designed for energy efficiency, hardware independent development and a high degree of modularity                                          | LGPL     | C        |
| [UBOS](http://ubos.net) <br> [![GitHub stars](https://img.shields.io/github/stars/uboslinux/ubos-admin.svg?style=social&label=Star&maxAge=2592000)]()                        | UBOS is an Arch-derived Linux distro optimized for cost-efficient administration Personal Servers and Indie IoT Devices                                                                                                                         | Linux    | many     |
| [Zephyr](https://www.zephyrproject.org/)                                                                                                                                     | Zephyr Project is a small, scalable real-time operating system for use on resource-constrained systems supporting multiple architectures.                                                                                                       | ASLv2    | C        |

## Remote Management

*Libraries that can be used to implement remote management of IoT devices*

### LWM2M

|                                                                                                  Name                                                                                                 |                                          Description                                          | License | Language |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|---------|----------|
| [Betwixt](https://github.com/zubairhamed/betwixt) <br> [![GitHub stars](https://img.shields.io/github/stars/zubairhamed/betwixt.svg?style=social&label=Star&maxAge=2592000)]()                        | Betwixt is a LWM2M Client and Server in Go                                                    | ASL     | Go       |
| [Eclipse Leshan](https://eclipse.org/leshan) <br> [![GitHub stars](https://img.shields.io/github/stars/eclipse/leshan.svg?style=social&label=Star&maxAge=2592000)]()                                  | Eclipse Leshan is a LWM2M implementation in Java                                              | EPL/EDL | Java     |
| [lwm2m-node-lib](https://github.com/telefonicaid/lwm2m-node-lib) <br> [![GitHub stars](https://img.shields.io/github/stars/telefonicaid/lwm2m-node-lib.svg?style=social&label=Star&maxAge=2592000)]() | lwm2m-node-lib is a library for building LWM2M applications (client and server) in Javascript | AGPL    | Node.js  |
| [Eclipse Wakaama](https://eclipse.org/wakaama) <br> [![GitHub stars](https://img.shields.io/github/stars/eclipse/wakaama.svg?style=social&label=Star&maxAge=2592000)]()                               | Eclipse Wakaama is a LWM2M implementation in C                                                | EPL/EDL | C        |
| [AwaLWM2M](https://github.com/FlowM2M/AwaLWM2M) <br> [![GitHub stars](https://img.shields.io/github/stars/flowm2m/awalwm2m.svg?style=social&label=Star&maxAge=2592000)]()                             | Awa LWM2M is an implementation of the OMA Lightweight M2M protocol in C                       |BSD-3 | C          |


### OMA-DM

|                                                                                      Name                                                                                      |                          Description                          | License | Language |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------|---------|----------|
| [libdmclient](https://github.com/01org/libdmclient) <br> [![GitHub stars](https://img.shields.io/github/stars/01org/libdmclient.svg?style=social&label=Star&maxAge=2592000)]() | libdmclient implements the client-side of OMA DM 1.2 protocol | ASL     | C        |

### SNMP

|                                                                                Name                                                                               |                                                    Description                                                    | License | Language |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------|---------|----------|
| [SNMP4J](http://www.snmp4j.org/)                                                                                                                                  | SNMP4J is an enterprise class free open source and state-of-the-art SNMP implementation for Java™ SE 1.4 or later | ASL     | Java     |
| [GoSNMP](https://github.com/alouca/gosnmp) <br> [![GitHub stars](https://img.shields.io/github/stars/alouca/gosnmp.svg?style=social&label=Star&maxAge=2592000)]() | A simple SNMP library written in Go                                                                               | BSD     | Go       |

### TR-069

|                                                                                  Name                                                                                  |                        Description                        | License | Language |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------|---------|----------|
| [netcwmp](https://github.com/netcwmp/netcwmp) <br> [![GitHub stars](https://img.shields.io/github/stars/netcwmp/netcwmp.svg?style=social&label=Star&maxAge=2592000)]() | A software client for enabling TR-069 in embedded devices | ASLv2   | C        |

## Robotics and Physical computing

|                                                                                     Name                                                                                    |                                                     Description                                                      | License | Language |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------|---------|----------|
| [Artoo](https://github.com/hybridgroup/artoo) <br> [![GitHub stars](https://img.shields.io/github/stars/hybridgroup/artoo.svg?style=social&label=Star&maxAge=2592000)]()    | Artoo is a micro-framework for robotics using Ruby.                                                                  | ASLv2   | Ruby     |
| [Cylon.js](https://github.com/hybridgroup/cylon) <br> [![GitHub stars](https://img.shields.io/github/stars/hybridgroup/cylon.svg?style=social&label=Star&maxAge=2592000)]() | Cylon.js is a JavaScript framework for robotics, physical computing, and the Internet of Things.                     | ASLv2   | Node.js  |
| [Gobot](https://github.com/hybridgroup/gobot) <br> [![GitHub stars](https://img.shields.io/github/stars/hybridgroup/gobot.svg?style=social&label=Star&maxAge=2592000)]()    | Gobot is a framework using the Go programming language for robotics, physical computing, and the Internet of Things. | ASLv2   | Go       |

## Security

### DNS-SEC

|                                                                                           Name                                                                                          |                                          Description                                           | License | Language |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------|---------|----------|
| [Dnsruby](https://github.com/alexdalitz/dnsruby) <br> [![GitHub stars](https://img.shields.io/github/stars/alexdalitz/dnsruby.svg?style=social&label=Star&maxAge=2592000)]()            | Dnsruby is a pure Ruby DNS client library which implements a stub resolver and supports DNSSEC | ASLv2   | Ruby     |
| [dnssecjava](https://github.com/ibauersachs/dnssecjava) <br> [![GitHub stars](https://img.shields.io/github/stars/ibauersachs/dnssecjava.svg?style=social&label=Star&maxAge=2592000)]() | A DNSSEC validating stub resolver for Java.                                                    | EPL     | Java     |

### DTLS

|                                                                                         Name                                                                                         |                                                                                                                     Description                                                                                                                      |    License     |  Language  |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------|------------|
| [DTLS Go](https://github.com/cfromknecht/dtls) <br> [![GitHub stars](https://img.shields.io/github/stars/cfromknecht/dtls.svg?style=social&label=Star&maxAge=2592000)]()             | DTLS 1.2 in Go                                                                                                                                                                                                                                       | MIT            | Go         |
| [Eclipse Scandium]( http://www.eclipse.org/californium) <br> [![GitHub stars](https://img.shields.io/github/stars/eclipse/californium.svg?style=social&label=Star&maxAge=2592000)]() | The Scandium (Sc) sub-project within Californium implements DTLS 1.2 to secure your application through ECC with pre-shared keys, certificates, or raw public keys.                                                                                  | EPL/EDL        | Java       |
| [Eclipse TinyDTLS]( http://www.eclipse.org/tinydtls)                                                                                                                                 | tinydtls is a library for Datagram Transport Layer Security (DTLS) covering both the client and the server state machine.  tinydtls is a library for Datagram Transport Layer Security (DTLS) covering both the client and the server state machine. | EPL/EDL        | C          |
| [mbed TLS](https://tls.mbed.org/)                                                                                                                                                    | mbed TLS (previously PolarSSL) is an implementation of the TLS and SSL protocols and the respective cryptographic algorithms and support code required.                                                                                              | ASLv2          | C          |
| [OpenSSL](https://www.openssl.org/)                                                                                                                                                  | OpenSSL is an open source project that provides a robust, commercial-grade, and full-featured toolkit for the Transport Layer Security (TLS) and Secure Sockets Layer (SSL) protocols.                                                               | OpenSSL/SSLeay | C/Assembly |
| [PyDTLS](https://github.com/rbit/pydtls) <br> [![GitHub stars](https://img.shields.io/github/stars/rbit/pydtls.svg?style=social&label=Star&maxAge=2592000)]()                        | Datagram Transport Layer Security for Python                                                                                                                                                                                                         | ASLv2          | Python     |

### TLS

|                 Name                |                                                                                      Description                                                                                       |    License     |  Language  |
|-------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------|------------|
| [mbed TLS](https://tls.mbed.org/)   | mbed TLS (previously PolarSSL) is an implementation of the TLS and SSL protocols and the respective cryptographic algorithms and support code required.                                | ASLv2          | C          |
| [OpenSSL](https://www.openssl.org/) | OpenSSL is an open source project that provides a robust, commercial-grade, and full-featured toolkit for the Transport Layer Security (TLS) and Secure Sockets Layer (SSL) protocols. | OpenSSL/SSLeay | C/Assembly |

## Workflow management

|                                                                                     Name                                                                                    |                                     Description                                     | License | Language |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------|---------|----------|
| [Node-RED](https://github.com/node-red/node-red) <br> [![GitHub stars](https://img.shields.io/github/stars/node-red/node-red.svg?style=social&label=Star&maxAge=2592000)]() | A visual tool for wiring the Internet of Things.                                    | ASL     | Node.js  |
| [huginn](https://github.com/cantino/huginn) <br> [![GitHub stars](https://img.shields.io/github/stars/cantino/huginn.svg?style=social&label=Star&maxAge=2592000)]()         | Huginn is a system for building agents that perform automated tasks for you online. | MIT     | Ruby     |

# Contributing

Contributions are very welcome! In order to be considered an Awesome Open IoT project you need the following:
* Valid [OSI approved license](https://opensource.org/licenses/alphabetical),
* Proven record of regular commits,
* Significant community interest shown through GitHub stars,
* Project is focused on solving problems that are specific to IoT.

Please also have a look at [this contributing guide](https://github.com/akullpp/awesome-java/blob/master/CONTRIBUTING.md) for some general guidelines.
