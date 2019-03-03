<!-- #################################################### -->
# Setup IOT in the Cloud #
<!-- #################################################### -->

## iot exe bmx console
If you have been through Mandie Quartly's [Introduction to Watson APIs and NodeRED](https://github.com/mandieq/node-red-exeter),
you should have an IBM Cloud console view similar to the following:

 ![iot exe bmx console](img/iot-exe-bmx-console.png)
You can see your NodeRED application, and the services that have been
connected to it.

## iot exe cat iot

Use the `Create resource` button and select the `Internet of Things` service.

 ![iot exe cat iot](img/iot-exe-cat-iot.png)

## iot exe add iot

Create a Lite plan instance of the "Internet of Things Platform" service

 ![iot exe add iot](img/iot-exe-add-iot.png)

## iot exe svc iot
Now launch the IOT Platform console

 ![iot exe svc iot](img/iot-exe-svc-iot.png)

## iot exe add iot dev

Here, you will register your Raspberry Pi as an IOT device, using
the `+ Add Device`

 ![iot exe add iot dev](img/iot-exe-add-iot-dev.png)

## iot exe add iot dev 2

All devices must belong to a particular device type category;
this is currently undefined

 ![iot exe add iot dev 2](img/iot-exe-add-iot-dev-2.png)

## iot exe add iot dev 3
Provide a name for the Device Type (* raspberry-pi *)

 ![iot exe add iot dev 3](img/iot-exe-add-iot-dev-3.png)

## iot exe add iot dev 4
Now provide the name for your device (* mypi *)

 ![iot exe add iot dev 4](img/iot-exe-add-iot-dev-4.png)

## iot exe add iot dev tok
At this stage in the device definition, the IOT Platform sets the
authentication token for the new device - this can be left to be
auto-generated, or manually created -- in this case provide
a fixed and memorable value (* exeter-4IR *)

 ![iot exe add iot dev tok](img/iot-exe-add-iot-dev-tok.png)

## iot exe add iot dev done
Almost finished - you have a last chance to cancel/change the
device registration -- as you have all the information needed,
click `Done`

 ![iot exe add iot dev done](img/iot-exe-add-iot-dev-done.png)

## iot exe view iot dev
You will see (for the last time) all the information needed by the device to
authenticate when transmitting or receiving messages:

 ![iot exe view iot dev](img/iot-exe-view-iot-dev.png)

## iot exe add iot dev list
You can see the new device in the Devices list

 ![iot exe add iot dev list](img/iot-exe-add-iot-dev-list.png)

## iot exe add iot dev events

If you click on the device, you will be shown the device status page,
which will show events/msgs as the arrive at the IOT Platform.

 ![iot exe add iot dev events](img/iot-exe-add-iot-dev-events.png)

## iot exe add iot connex
Now, a few steps to allow both NodeRED on IBM Cloud, and NodeRED on
the Raspberry-Pi to exchange messages with your IOT Platform.

First will be to connect the service instance with the existing
NodeRED application

 ![iot exe add iot connex](img/iot-exe-add-iot-connex.png)

## iot exe add iot connex app

Click `Connect` for the NodeRED app:

 ![iot exe add iot connex app](img/iot-exe-add-iot-connex-app.png)

## iot exe add iot connex restage
As before when creating a connection to a CloudFoundry application,
you will be prompted to restart the app with new configuration -
click `Restage`.

 ![iot exe add iot connex restage](img/iot-exe-add-iot-connex-restage.png)
