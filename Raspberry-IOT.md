<!-- #################################################### -->
# Raspberry Pi setup #
<!-- #################################################### -->

## iot exe pi ssh
Login to your (named) Pi - replace "raspberrypi" with the name of device
you're associated with (TETHYS.local, for example).

The password for the * pi * user is set to the default (* raspberry *)

 ![iot exe pi ssh](img/iot-exe-pi-ssh.png)

## iot exe pi ssh login
After login, you can change the password if you like

 ![iot exe pi ssh login](img/iot-exe-pi-ssh-login.png)

## iot exe pi nodered install
NodeRED has been installed on your Pi, consistent with
instructions from the [NodeRED site](https://nodered.org/docs/hardware/raspberrypi)
 ![iot exe pi nodered install](img/iot-exe-pi-nodered-install.png)

## iot exe pi nodered install cmd
 ![iot exe pi nodered install cmd](img/iot-exe-pi-nodered-install-cmd.png)

## iot exe pi nodered install progress
The NodeRED install will
+ remove previous version(s)
+ install the current long time support version of Node.js
+ install Node Package Manager (npm)
+ install NodeRED
+ set up NodeRED in the local user context

 ![iot exe pi nodered install progress](img/iot-exe-pi-nodered-install-progress.png)

## iot exe pi nodered install done
Once installation is complete, launching NodeRED is easy with the
`node-red-start` command

 ![iot exe pi nodered install done](img/iot-exe-pi-nodered-install-done.png)

## iot exe pi nodered started
running the command interactively, means that you will see the console and error
logs for the application

 ![iot exe pi nodered started](img/iot-exe-pi-nodered-started.png)

## iot exe pi nodered ide
After NodeRED starts, you can connect to it via a browser using
`https://<your pi name>.local:1880/`

 ![iot exe pi nodered ide](img/iot-exe-pi-nodered-ide.png)

## iot exe pi nodered install scxiot
To be able to readily generate and consume IOT events with the IBM IOT Platform,
install the `node-red-contrib-scx-ibmiotapp` module - this has more flexibility
than the `Watson IOT` module installed by default.

 ![iot exe pi nodered install scxiot](img/iot-exe-pi-nodered-install-scxiot.png)

## iot exe pi nodered iot in
Set up a subscriber node to listen for events in your IOT instance

 ![iot exe pi nodered iot in](img/iot-exe-pi-nodered-iot-in.png)

## iot exe pi nodered iot out
Configure a publisher node to be able to send IOT events

 ![iot exe pi nodered iot out](img/iot-exe-pi-nodered-iot-out.png)

## iot exe pi nodered iot testdata
Create some test data (in standard format for devices), and publish

 ![iot exe pi nodered iot testdata](img/iot-exe-pi-nodered-iot-testdata.png)

## iot exe pi nodered iot testdata json
 ![iot exe pi nodered iot testdata json](img/iot-exe-pi-nodered-iot-testdata-json.png)

## iot exe view iot keys
To configure the IOT nodes to connect to the IBM Cloud IOT Platform instance, you will need a security key -- return to the IOT Platform Console and create an API key

 ![iot exe view iot keys](img/iot-exe-view-iot-keys.png)

## iot exe add iot api key
 ![iot exe add iot api key](img/iot-exe-add-iot-api-key.png)

## iot exe add iot api key done
 ![iot exe add iot api key done](img/iot-exe-add-iot-api-key-done.png)

## iot exe add iot api key list
*NOTE*: you need to copy the key information shown here to a notepad or file, so you can add it to the NodeRED configuration on the Raspberry Pi

 ![iot exe add iot api key list](img/iot-exe-add-iot-api-key-list.png)

## iot exe add iot api key view
 ![iot exe add iot api key view](img/iot-exe-add-iot-api-key-view.png)

## iot exe pi nodered iot api key
Add the API Key name and the API token (which you saved from the Cloud IOT Platform, earlier)

 ![iot exe pi nodered iot api key](img/iot-exe-pi-nodered-iot-api-key.png)

## iot exe pi nodered iot out config
 ![iot exe pi nodered iot out config](img/iot-exe-pi-nodered-iot-out-config.png)

## iot exe pi nodered iot in config
 ![iot exe pi nodered iot in config](img/iot-exe-pi-nodered-iot-in-config.png)

## iot exe sec iot dev tls
For your Raspberry Pi to be able to connect reliably to IBM Cloud IOT Platform, you should modify the network security settings to make TLS optional.

 ![iot exe sec iot dev tls](img/iot-exe-sec-iot-dev-tls.png)

## iot exe sec iot dev optional
 ![iot exe sec iot dev optional](img/iot-exe-sec-iot-dev-optional.png)

## iot exe sec iot dev tls warn
 ![iot exe sec iot dev tls warn](img/iot-exe-sec-iot-dev-tls-warn.png)

## iot exe pi nodered iot publish
Now you're ready to publish messages using the IOT service
 ![iot exe pi nodered iot publish](img/iot-exe-pi-nodered-iot-publish.png)

## iot exe pi nodered iot out set
 ![iot exe pi nodered iot out set](img/iot-exe-pi-nodered-iot-out-set.png)

## iot exe pi nodered iot in set
 ![iot exe pi nodered iot in set](img/iot-exe-pi-nodered-iot-in-set.png)

## iot exe pi nodered iot first msg
 ![iot exe pi nodered iot first msg](img/iot-exe-pi-nodered-iot-first-msg.png)


## iot exe bmx nodered nostart error
 ![iot exe bmx nodered nostart error](img/iot-exe-bmx-nodered-nostart-error.png)

## iot exe pi nodered install arduino
 ![iot exe pi nodered install arduino](img/iot-exe-pi-nodered-install-arduino.png)

## iot exe pi nodered arduino in
 ![iot exe pi nodered arduino in](img/iot-exe-pi-nodered-arduino-in.png)

## iot exe pi arduino sketch firmata
 ![iot exe pi arduino sketch firmata](img/iot-exe-pi-arduino-sketch-firmata.png)

## iot exe pi arduino sketch upload
 ![iot exe pi arduino sketch upload](img/iot-exe-pi-arduino-sketch-upload.png)

## iot exe pi arduino port
 ![iot exe pi arduino port](img/iot-exe-pi-arduino-port.png)

## iot exe pi nodered arduino port
 ![iot exe pi nodered arduino port](img/iot-exe-pi-nodered-arduino-port.png)

## iot exe pi nodered arduino in lux
 ![iot exe pi nodered arduino in lux](img/iot-exe-pi-nodered-arduino-in-lux.png)

## iot exe pi nodered arduino in lux data
 ![iot exe pi nodered arduino in lux data](img/iot-exe-pi-nodered-arduino-in-lux-data.png)

## iot exe pi nodered arduino in rate
 ![iot exe pi nodered arduino in rate](img/iot-exe-pi-nodered-arduino-in-rate.png)

## iot exe pi nodered arduino in rate set
 ![iot exe pi nodered arduino in rate set](img/iot-exe-pi-nodered-arduino-in-rate-set.png)

## iot exe pi nodered arduino iot msgs
 ![iot exe pi nodered arduino iot msgs](img/iot-exe-pi-nodered-arduino-iot-msgs.png)

## iot exe pi nodered arduino in lux format
 ![iot exe pi nodered arduino in lux format](img/iot-exe-pi-nodered-arduino-in-lux-format.png)

## iot exe events iot list
 ![iot exe events iot list](img/iot-exe-events-iot-list.png)

## iot exe pi nodered arduino out set
 ![iot exe pi nodered arduino out set](img/iot-exe-pi-nodered-arduino-out-set.png)

## iot exe bmx iot in creds
 ![iot exe bmx iot in creds](img/iot-exe-bmx-iot-in-creds.png)

## iot exe bmx iot in settings
 ![iot exe bmx iot in settings](img/iot-exe-bmx-iot-in-settings.png)

## iot exe bmx iot in msgs
 ![iot exe bmx iot in msgs](img/iot-exe-bmx-iot-in-msgs.png)

## iot exe bmx iot out data
 ![iot exe bmx iot out data](img/iot-exe-bmx-iot-out-data.png)

## iot exe bmx iot out settings command
 ![iot exe bmx iot out settings command](img/iot-exe-bmx-iot-out-settings-command.png)

## iot exe bmx iot out data test
 ![iot exe bmx iot out data test](img/iot-exe-bmx-iot-out-data-test.png)

## iot exe pi nodered iot in command
 ![iot exe pi nodered iot in command](img/iot-exe-pi-nodered-iot-in-command.png)

## iot exe pi nodered iot in command format 1
 ![iot exe pi nodered iot in command format 1](img/iot-exe-pi-nodered-iot-in-command-format-1.png)

## iot exe pi nodered iot save db
 ![iot exe pi nodered iot save db](img/iot-exe-pi-nodered-iot-save-db.png)

## iot exe pi nodered iot in commands
 ![iot exe pi nodered iot in commands](img/iot-exe-pi-nodered-iot-in-commands.png)

## iot exe pi nodered iot view db
 ![iot exe pi nodered iot view db](img/iot-exe-pi-nodered-iot-view-db.png)
