# RFM-LoRa-Shield-Examples
This is an example tutorial of point-to-point wireless communication between 2 Arduinos using RFM LoRa Shields.

## Basic Requirements
1. 2 RFM LoRa Shields
2. 2 Arduino-compatible boards
3. USB cable and other accessories to upload Arduino program
4. Arduino IDE software

## Basic Hardware Setup
1. Stack RFM LoRa Shield onto Arduino compatible board with antenna installed as shown in picture below. In this case we are using CT-UNO.
<p><b>CT-UNO with LoRa Shield on top</b></p>
![alt tag](https://raw.githubusercontent.com/CytronTechnologies/Hackathon-Penang-2016/master/img/IMG-20161111-WA0001.jpg)
<p><b>CT-UNO + LoRa Shield with antenna installed</b></p>
![alt tag](https://raw.githubusercontent.com/CytronTechnologies/Hackathon-Penang-2016/master/img/Lora%20Full.png)
2. Prepare **2** sets for this.

## RadioHead Library Installation
1. Download the zip file from [here](https://github.com/CytronTechnologies/RadioHead).
2. Open Arduino IDE, go to **Sketch > Include Library > Add .ZIP Library**, choose the downloaded zip file and click Open.

## Uploading the Sketches

Download the sketches as zip files from this page **OR** git clone this repo.

### Client ###
1. Grab one set of RFM LoRa Shield + Arduino that you have setup just now. We call it as **Arduino LoRa Client**.
2. Open and upload ``rf95_client.ino`` sketch to **Arduino LoRa Client**.

### Server ###
1. Grab another set of RFM LoRa Shield + Arduino that you have setup just now. We call it as **Arduino LoRa Server**.
2. Open and upload ``rf95_server.ino`` sketch to **Arduino LoRa Server**.
