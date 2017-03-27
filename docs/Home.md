# Point-to-point Communication of Arduinos with RFM LoRa Shield 
This is an example tutorial of point-to-point wireless communication between 2 Arduinos using RFM LoRa Shields.

## Overview
1. [Basic Requirements](#basic-requirements)
2. [Basic Hardware Setup](#basic-hardware-setup)
3. [RadioHead Library Installation](#radiohead-library-installation)
4. [Uploading the Sketches](#uploading-the-sketches)
5. [Arduino Sketches Overview](https://github.com/CytronTechnologies/RFM-LoRa-Shield-Examples/wiki/Arduino-Sketches-Overview)
6. [Arduino Serial Monitor Screenshots](#arduino-serial-monitor-screenshots)


## Basic Requirements
1. 2 RFM LoRa Shields
2. 2 Arduino-compatible boards
3. USB cable/accessories to upload Arduino program
4. Arduino IDE software


## Basic Hardware Setup
1. Stack RFM LoRa Shield onto Arduino compatible board with antenna installed as shown in picture below. In this case we are using CT-UNO.
2. Prepare **2** sets for this. <p>**CT-UNO with LoRa Shield on top**</p><p>**CT-UNO + LoRa Shield with antenna installed**</p>

## RadioHead Library Installation
1. Download the zip file from [here](https://github.com/CytronTechnologies/RadioHead).
2. Open Arduino IDE, go to **Sketch > Include Library > Add .ZIP Library**, choose the downloaded zip file and click Open.


## Uploading the Sketches

1. Download the Arduino sketches as zip files **OR** git clone this repo from [here](https://github.com/CytronTechnologies/RFM-LoRa-Shield-Examples).
2. Grab one set of RFM LoRa Shield + Arduino that you have setup just now. We call it as **Arduino LoRa Client**.
3. Open and upload ``rf95_client.ino`` sketch to **Arduino LoRa Client**.
4. Grab another set of RFM LoRa Shield + Arduino that you have setup just now. We call it as **Arduino LoRa Server**.
5. Open and upload ``rf95_server.ino`` sketch to **Arduino LoRa Server**.


## Arduino Sketches Overview

> Refer [here](https://github.com/CytronTechnologies/RFM-LoRa-Shield-Examples/wiki/Arduino-Sketches-Overview).


## Arduino Serial Monitor Screenshots
* <p><b>Arduino LoRa Server</b></p>
![](https://raw.githubusercontent.com/CytronTechnologies/RFM-LoRa-Shield-Examples/master/img/lorarx.png)
* <p><b>Arduino LoRa Client</b></p>
![](https://raw.githubusercontent.com/CytronTechnologies/RFM-LoRa-Shield-Examples/master/img/loratx.png)