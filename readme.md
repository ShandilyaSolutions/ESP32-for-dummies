# Getting Started with an ESP32 board:

## Hello World using ESP32

Just like all traditional programming language you must start your ESP32 journey by performing the Hello World ritual. 

I am assuming that you have already configured Arduino IDE for ESP32. 

### Code

Paste the code from this  file into the new file : [HelloWorld](https://github.com/ShandilyaSolutions/ESP32-for-dummies/blob/main/hello_world.ino)
 Save it!
 
 Compile it!

 And upload it to your ESP32 board. Once the code is uploaded open the Serial Monitor window by pressing *CTRL+Shift+M*. 

You will see the following screen: ![Serial Monitor](https://makeabilitylab.github.io/physcomp/arduino/assets/images/SerialPrintHelloWorld_SerialMonitor.png)

Change the Serial.print() line's message and play with the different messages displayed in the plotter.

*Note : You will have to compile the code and reupload it to esp32. After reuploading is done start Serial Monitor and the change will be visible. **If it is not visible then disconnect and reconnect the USB again and again until you see the output.*** 

## Working with Wifi functionalities of ESP32
ESP32 is a versatile microcontroller with inbuilt Wifi which is a really great functionality making this microcontroller ideal for IoT applications.

All the functionalities of Wifi are accessed using :  `WiFi.h` class whose documentation can be found [here](https://randomnerdtutorials.com/esp32-useful-wi-fi-functions-arduino/).

We will be working out with the functionalities in a systematic method as this one is pretty much advance.

### Scanning all the nearby Wifi networks using ESP32:
Here we will be using our ESP to scan all the available networks and display them in Serial Monitor.  

Copy the code from [this](https://github.com/ShandilyaSolutions/ESP32-for-dummies/blob/main/wifi.ino) file and paste it into the Arduino IDE. Compile it and upload it. Open a Serial Monitor and you shall see the available networks displayed in it.

![alt Wifi code output](https://i0.wp.com/randomnerdtutorials.com/wp-content/uploads/2021/02/Scan-WiFi-Networks-ESP32-Arduino-IDE-Serial-Monitor.png?resize=733%2C541&quality=100&strip=all&ssl=1)
