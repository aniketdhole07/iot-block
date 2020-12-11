# IoTBlock

[PPT Link](https://docs.google.com/presentation/d/1r3g_alNW4ZRGk-2TBVW8Y1ViM7jbiwpWlvrCDx2_vTg/edit?usp=sharing)

It reads the data from IoT devices via HTTP Requests and adds it to a Block of Blockchain,and also suggest the user if it is advisable to go out of his house based on his location and sensor data

<img src="https://i.ibb.co/fNgvYVR/esp8266-dht22-breadboard.jpg" alt="esp8266-dht22-breadboard" border="0">


## Usage

1. Make the NodeMCU wiring 

<img src="https://i.ibb.co/NVMsBK6/dht22-esp8266-wiring.png" alt="dht22-esp8266-wiring" border="0">

2. Connect it to same wifi and flash the nodemcu ino file

3. Run the App by cloning the repo and ,

```
npm install .
npm start
```

And Open `http://localhost:3001/block-data`
