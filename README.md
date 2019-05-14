# MQTT Client using Websockets and Mapfit API

This is a MQTT client for the browser.

## How it works:

* The client must be configured to connect with a MQTT broker (It can be Mosquitto) of your preference.

  * (Obs: The broker have to be configured to connect through Websockets)

* Once the connection is made, the client can receive coordinate data from other clients and print the geolocalization on the map.

## Requeriments:

* npm install mqtt --save

* npm install -g browserify 
* cd node_modules/mqtt
* npm install . 
* browserify mqtt.js -s mqtt > browserMqtt.js 
