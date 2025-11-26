# How connect MikroTik routers to Mqtt broker
## original document https://help.mikrotik.com/docs/spaces/ROS/pages/46759978/MQTT

* Install the iot package, from the System/Packages menu
* The installation will restart the router
* In the IoT/MQTT menu add a broker
* If your broker has SSL you can enable it, but you need trust the root certificates for many common certificate authorities in the System/certificate/settings menu.
* Go to System/Certificates and create one cert, if you have already create it you can skip this step.
* Now you can select the cert on the Certificate Broker.
* Test the mqtt broker connection publish something
