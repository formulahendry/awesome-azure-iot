# Awesome Azure IoT ![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) [![Build Status](https://travis-ci.org/formulahendry/awesome-azure-iot.svg?branch=master)](https://travis-ci.org/formulahendry/awesome-azure-iot)

A curated list of awesome Azure Internet of Things projects and resources.

- [Hardware](#hardware)
- [Operating System](#operating-system)
- [IoT Clouds](#iot-clouds)
- [Get started with IoT Hub](#get-started-with-iot-hub)
- [Framework](#framework)
- [SDK](#sdk)
- [Libraries and Tools](#libraries-and-tools)
- [Resources](#resources)

## Hardware

- [Azure Certified for IoT device catalog](https://catalog.azureiotsuite.com/) - Certified for IoT devices tailored to your needs.
- [Microsoft Azure IoT Starter Kits](https://azure.microsoft.com/en-us/develop/iot/starter-kits/) - Start innovating today with kits that include development boards that are 'Azure Certified for IoT', sensors and actuators. Simple user-friendly tutorials help you seamlessly connect your devices to the cloud with Microsoft Azure IoT.

## Operating System

- [Windows 10 IoT Core](https://developer.microsoft.com/en-us/windows/iot) -  Windows 10 IoT is a family of Windows 10 editions targeted towards a wide range of intelligent devices, from small industrial gateways to larger more complex devices like point of sales terminals and ATMs..

## IoT Clouds

- [Azure IoT Hub](https://azure.microsoft.com/en-us/services/iot-hub/) - Connect, monitor, and manage billions of IoT assets. Azure IoT Hub is a fully managed service that enables reliable and secure bidirectional communications between millions of IoT devices and a solution back end.
- [Azure Event Hubs](https://azure.microsoft.com/en-us/services/event-hubs/) - Cloud-scale telemetry ingestion from websites, apps, and any streams of data.
- [Azure Stream Analytics](https://azure.microsoft.com/en-us/services/stream-analytics/) - Real-time data stream processing from millions of IoT devices.

## Get started with IoT Hub

- [Simulated device](https://docs.microsoft.com/en-us/azure/iot-hub/iot-hub-node-node-getstarted) - Connect your simulated device to your IoT hub using Node.js.
- [Raspberry Pi 3](https://docs.microsoft.com/en-us/azure/iot-hub/iot-hub-raspberry-pi-kit-node-get-started) - Connect your Raspberry Pi 3 device to your IoT hub using Node.js.
- [Adafruit Feather M0 WiFi](https://docs.microsoft.com/en-us/azure/iot-hub/iot-hub-adafruit-feather-m0-wifi-kit-arduino-get-started) - Get started with your Arduino board: Adafruit Feather M0 WiFi.
- [Adafruit Feather HUZZAH ESP8266](https://docs.microsoft.com/en-us/azure/iot-hub/iot-hub-arduino-huzzah-esp8266-get-started) - Get started with your Arduino board: Adafruit Feather HUZZAH ESP8266.
- [Sparkfun ESP8266 Thing Dev](https://docs.microsoft.com/en-us/azure/iot-hub/iot-hub-sparkfun-esp8266-thing-dev-get-started) - Get started with your Arduino board: Sparkfun ESP8266 Thing Dev.
- [Intel Edison](https://docs.microsoft.com/en-us/azure/iot-hub/iot-hub-intel-edison-kit-c-get-started) - Connect your Intel Edison device to your IoT hub using C.
- [IoT Gateway Starter Kit](https://docs.microsoft.com/en-us/azure/iot-hub/iot-hub-gateway-kit-c-get-started) - Get started with IoT Gateway Starter Kit with a SensorTag.

## Framework

- [Azure IoT Protocol Gateway](https://github.com/Azure/azure-iot-protocol-gateway) - Azure IoT protocol gateway is a framework for protocol adaptation that enables bi-directional communication with Azure IoT Hub. It is a pass-through component that bridges traffic between connected IoT devices and IoT Hub.

## SDK

- [Azure IoT device SDK](https://docs.microsoft.com/en-us/azure/iot-hub/iot-hub-devguide-sdks#azure-iot-device-sdk) - The Microsoft Azure IoT device SDKs contain code that facilitates building devices and applications that connect to and are managed by Azure IoT Hub services.
- [Azure IoT service SDK](https://docs.microsoft.com/en-us/azure/iot-hub/iot-hub-devguide-sdks#azure-iot-service-sdk) - The Azure IoT service SDKs contain code to facilitate building applications that interact directly with IoT Hub to manage devices and security.
- [Azure IoT Gateway SDK](https://github.com/Azure/azure-iot-gateway-sdk) - Azure IoT Gateway SDK contains the infrastructure and modules to create IoT gateway solutions. You can extend the SDK to create gateways tailored to any end-to-end scenario.

## Libraries and Tools

- [PlatformIO for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=formulahendry.platformio) - PlatformIO is an open source ecosystem for IoT development. It supports 350+ embedded boards, 20+ development platforms and 10+ frameworks.
- [Azure IoT Toolkit](https://marketplace.visualstudio.com/items?itemName=formulahendry.azure-iot-toolkit) - Azure IoT Toolkit Extension for Visual Studio Code: Interact with Azure IoT Hub; IoT Device Management; Discover Ethernet, USB serial, WiFi connected devices; Deploy and run code in remote machine.
- [Azure IoT Web Client](https://azure-iot.github.io) - A web-based client tool for Azure IoT Hub to send and monitor device-to-cloud messages.
- [Azure CLI](https://docs.microsoft.com/en-us/cli/azure/iot) - Commands to connect, monitor, and control millions of IoT assets.
- [IoT Hub REST API](https://docs.microsoft.com/en-us/rest/api/iothub/) - The REST APIs for IoT Hub offer programmatic access to the device and messaging services, as well as the resource provder, in IoT Hub.
- [IoT Hub Explorer](https://github.com/azure/iothub-explorer) - A CLI tool to manage device identities in your IoT hub registry, send and receive messages and files from your devices, and monitor your IoT hub operations.
- [Device Explorer](https://github.com/Azure/azure-iot-sdk-csharp/tree/master/tools/DeviceExplorer) - This tool enables you to perform operations such as manage the devices registered to an IoT hub, view device-to-cloud messages sent to an IoT hub, and send cloud-to-device messages from an IoT hub. Note this tool only runs on Windows.
- [IoT Hub Diagnostics Tool](https://github.com/azure/iothub-diagnostics) - This tool is provided to help diagnose issues with a device connecting to Azure IoT Hubs.

## Resources

- [Azure IoT Developer Center](https://azure.microsoft.com/en-us/develop/iot/) - Get started with Azure IoT Suite and IoT Hub and learn how easy it is to connect your IoT devices to Microsoft Azure.
- [Azure IoT Hub Code Samples](https://azure.microsoft.com/en-us/resources/samples/?service=iot-hub) - Learn to interact with Azure IoT Hub through code.
- [Azure IoT Hub updates](https://azure.microsoft.com/en-us/updates/?product=iot-hub) - Service Updates for Azure IoT Hub.
- [Azure IoT Hub limits](https://docs.microsoft.com/en-us/azure/azure-subscription-service-limits#iot-hub-limits) - List the limits associated with the different service tiers (S1, S2, S3, F1).
- [Azure IoT Suite](https://azure.microsoft.com/en-us/suites/iot-suite/) - Get started quickly with Microsoft Azure IoT Suite. Use preconfigured solutions, and accelerate the development of your Internet of Things (IoT) solution.
- [Internet of Things partners](https://www.microsoft.com/en-us/internet-of-things/find-a-partner) - Connect with a partner to unleash the powerful potential and business value of the Internet of Things (IoT). Whether you’re looking for a complete IoT solution, or building your own using certified devices, engage with an Azure IoT partner to tailor a solution for the needs of your business.
- [Azure Blog for Internet of Things](https://azure.microsoft.com/en-us/blog/topics/internet-of-things/) - The official Microsoft Azure Blog for topics about Internet of Things.
