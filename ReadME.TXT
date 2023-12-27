Home-Automation-System

IOT based home automation system.

Basic idea:

Whatever the future of IoT brings, smart devices will become entangled in our lives. Here we control AC bulb and security gate using NodeMCU.

Design and work:

Here we have used Blynk as a GUI to control the NodeMCU. We create an access code through the app, if it matches the access code listed in the code, the gate will open via the servo motor. For a light bulb, if we put a high signal in the app, it will create a low signal on the relay because it is an active low pin.

Components required:

Arduino Nano/Uno, NodeMCU (Esp8266), Relay Module, Servo Motor, IC 7809, Breadboard, Wires to Slice, Wires Male-Plug, Wires Male-Plug, 12V Battery, Light Bulb.

Run:

Run "bulb using arduino" code in arduino IDE and upload to arduino Nano and run "Home_Automation_Using_Node_MCU" code in arduino IDE and upload to NodeMCU.