# Tasmota-RGBCCT-DH-for-SmartThings-Classic-with-MQTT - V1.1.1
This is a feature rich device handler for Tasmota based RGBCCT bulbs in the SmartThings environment. It supports the following capabilities via the SmartThings Classic UI.

Direct IP (1:1)
*Off\On
*Dimmer
*Color Picker
*Color Temp
*Preset Whites
*Custom Colors
*Sync w/Bulb
*Fade
Boot Color
Poll\Sync
Update DNI
WiFi Strength
*Items are also supported via MQTT Mode (1:N)

Follow these instructions to install the Device Handler and setup your first device.
To install the Devie Handler Log in to the SmartThings IDE (https://graph.api.smartthings.com/)\ Go to My Device Handlers
Click Create New Device Handler
In the From Code tab paste in the Groovy code from this repository.
Click Create
Click Publish --> For Me
To create a new device go to My Devices
Click New Device
Fill out the details. Give it any Device Network Id, this will be automatically changed after install.
For Type scroll to the bottom of the dropdown and select 'Tasmota RGBW Bulb w/MQTT for ST Classic V1.1.1'
Click Create
Open the newly created device in SmartThings Classic and go to preferences.
Enter the IP Address of your Tasmota RBGW device and enter username and password if required.
Click Save
The DNI will update automatically and your device should now be operational.
Now read the documentation link below for more info on the features and operation of the Device Handler..\

You can find the documentation here: 

You can find the code here: 

You can find a video walkthrough demonstrating the capabilities of the device handler here: https://youtu.be/hC1wcNZveCo

The interface was developed on an Android phone for the SmartThings Classic interface but should work with other form factors and OS variants. All testing was performed with Tasmota RGBW devices V6.0 and above.
