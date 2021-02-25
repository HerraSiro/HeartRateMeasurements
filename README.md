**Average Heart Rate Measurements**

Purpose of this project was to create a simple heart rate measuring system and an Android app that will display the average heart rate in real time.

Used materials:

For the heart rate measurements, MAX30102 sensor module was used. 
https://www.maximintegrated.com/en/products/interface/sensor-interface/MAX30102.html

For the Wi-Fi connection, Arduino compatible ESP8266 module was used.
https://www.espressif.com/en/products/socs/esp8266

Google Firebase was used to store and load the data. 
https://firebase.google.com/

The Androip app was developed with Android Studio. 
https://developer.android.com/

Visual Studio Code code editor was used as a code platform. 
https://code.visualstudio.com/

**Measurement system:** The MAX30102 module is connected to ESP8266 module directly with jump wires. Each measurement last for 5 seconds (Measuring time can be easily modified if necessary.) and after that measuring result is uploaded to the Google Firebase with Wi-Fi connection. 

**Graphical User Interface (GUI):** User can choose from two options: MEASURE HEARBEAT and MEASURE TEMPERATURE. The temperature measurement is an extension of this project. When MEASURE HEARTBEAT icon is clicked, new window is opened. There user can start and stop measurement whenever he/she wants. Current measurement result is displayed inside the white box.

![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)

