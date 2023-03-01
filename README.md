# smart-home-automation-
SMART HOME AUTOMATION SYSTEM :


Introduction:

The project aims at designing an advanced home automation system using normal web server and Wi-Fi technology.

The devices can be switched ON/OFF and sensors can be read using a Personal Computer (PC) as well as from your mobile phone through Wi-Fi.


Dependencies:


For this we need to install the following software:

1)Arduino IDE

2)Sinric Pro


Basic Usage:


In order to use this project,first of all you need to install all the dependencies on your device.


Here in order to make the work simpler we will be installing the Arduino IDE software.


After that we use Blynk IOT web server for designing switchs i.e (ON/OFF button) and UI.


Method of installation:


Arduino IDE Installation:

Step 1 − First you must have your Arduino board (you can choose your favorite board) and a USB cable. 

In case you use Arduino UNO you will need a standard USB cable (A plug to B plug) the kind you would connect to a USB.


Step 2 − Download Arduino IDE Software.

You can get different versions of Arduino IDE from the Download page on the Arduino Official website.
 
You must select your software, which is compatible with your operating system (Windows, IOS, or Linux). 

After your file download is complete, unzip the file.


Step 3 − Power up your board.

The Arduino Uno, Mega, Duemilanove and Arduino Nano automatically draw power from either, the USB connection to the computer or an external power supply. 

If you are using an Arduino Diecimila, you have to make sure that the board is configured to draw power from the USB connection. 

The power source is selected with a jumper, a small piece of plastic that fits onto two of the three pins between the USB and power jacks. 

Check that it is on the two pins closest to the USB port.

Connect the Arduino board to your computer using the USB cable. The green power LED (labeled PWR) should glow.


Step 4 − Launch Arduino IDE.

After your Arduino IDE software is downloaded, you need to unzip the folder.
 
Inside the folder, you can find the application icon with an infinity label (application.exe). Double-click the icon to start the IDE.


Step 5 − Open your first project.

Once the software starts, you have two options −

Create a new project.

Open an existing project example.

To create a new project, select File → New.

To open an existing project example, select File → Example → Basics → Blink.

Here, we are selecting just one of the examples with the name Blink.
 
It turns the LED on and off with some time delay. You can select any other example from the list.


Step 6 − Select your Arduino board.

To avoid any error while uploading your program to the board, you must select the correct Arduino board name, 

which matches with the board connected to your computer.

Go to Tools → Board and select your board.

Here, we have selected Arduino Uno board according to our tutorial, but you must select the name matching the board that you are using.


Step 7 − Select your serial port.

Select the serial device of the Arduino board. Go to Tools → Serial Port menu. 

This is likely to be COM3 or higher (COM1 and COM2 are usually reserved for hardware serial ports). 

To find out, you can disconnect your Arduino board and re-open the menu, the entry that disappears should be of the Arduino board. 

Reconnect the board and select that serial port.


Step 8 − Upload the program to your board.

Before explaining how we can upload our program to the board, 

we must demonstrate the function of each symbol appearing in the Arduino IDE toolbar.

A − Used to check if there is any compilation error.

B − Used to upload a program to the Arduino board.

C − Shortcut used to create a new sketch.

D − Used to directly open one of the example sketch.

E − Used to save your sketch.

F − Serial monitor used to receive serial data from the board and send the serial data to the board.

ow, simply click the "Upload" button in the environment.

Wait a few seconds; you will see the RX and TX LEDs on the board, flashing. 

If the upload is successful, the message "Done uploading" will appear in the status bar.



Installation Of Sinric Pro:


Create the Sinric Pro Account.

Sinric Pro Login

Create a Room in Sinric Pro

Before adding the devices, first you have to create room in the Sinric Pro.

Steps for creating rooms in Sinric Pro:

Goto Rooms in the left side menu.
Click on Add Room button.
Enter the Room Name and Description.
Click on Save.

Add Devices in Sinric Pro

Enter the Device details:

Enter the Device Name and Description.
Then select the Device Type as per the requirement. Here I have selected device type as Switch, as I will control the SPDT relay.
Then select the Room for the device.
After that click on Next.

Setup Push Notification to the Mobile

If you want any push notifications related to this device, then you can turn on the notifications.
This field is optional.
Click on Next.

Sinric API KEY & API SECRET

Before uploading any example sketch to ESP8266 or ESP32, you have to enter the Sinric API KEY and API SECRET

To get the API KEY and API SECRET, you have to go to Credentials from left side menu.

#define WIFI_SSID         "YOUR-WIFI-NAME"    
#define WIFI_PASS         "YOUR-WIFI-PASSWORD"
#define APP_KEY           "YOUR-APP-KEY"
#define APP_SECRET        "YOUR-APP-SECRET"

After that, enter the APP KEY and APP SECRET with Wi-Fi name and Wi-Fi password in the code.

Also enter the device id in the code. You will find the Device ID from Devices menu.

Installation Process:
1. Download the Windows CH340 Driver.
2. Unzip the file.
3. Run the installer which you unzipped.
4. In the Arduino IDE when the CH340 is connected you will see a COM Port in the Tools > Serial Port menu, the COM number for your device may vary depending on your system.



With this your device acquired all dependencies to run our project.
