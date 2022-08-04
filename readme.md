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
