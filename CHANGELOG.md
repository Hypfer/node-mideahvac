## 0.1.12

* When parsing the C0 response the turbo property is now set when the strong and/or the turbo bit has been set
* Changed the setStatus command to also set the stronger bit when the turbo mode must be set
* The function to add the header now also takes a parameter to specify the agreement version
* Changed the getCapabilities command (no impact on response)
* Changed the getStatus command (no impact on response)
* Fixed bug in sendNetworkNotification (AP mode changed into client mode) this prevents the WiFi symbol from disappearing after approx. 20s
* Continue initialization even when a unit does not support the sendNetworkNotification and/or getCapabilities commands
* Updated unit tests

## 0.1.11

* Fixed bug in setting the horizontalSwingActive property.


## 0.1.10

* Send network status notification message during initialization of the serialbridge communication method. The result is the WiFi symbol will be shown in the dispay of the AC unit.