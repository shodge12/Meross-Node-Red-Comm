# Meross-Node-Red-Comm

The full intent of this project is to provide a link between Homeseer via MQTT to various Meross wireless items.  The code handles configuration of of the device and binds it to your local wifi and provides a address to your local MQTT server.  The code provides a ultra simplified MQTT interface to the Meross devices.  It handles ToggleX (on/offs) and Light (dim) primatives.

The dim interface provides a single interface topic for on/off and dim functions.  Dim 0 = off, Dim 100 = on, and dim 1-99 provides brightness levels.

The code has been validated against MSS425 (power strip) and the MSS560 (wall dimmer).

There are 3 releases of the code (flow.json)....
V3.00 is the working Homeseer to Meross working version.

V2.00 is a similar version to V3.00 but contains a logic error in the dim simulation of on/off functtions.

master is the original code which is a good starting point if you just want to learn to talk to the meross devices...

A [Wiki](../../wiki) will be setup for configuring the full Homeseer to Meross driver.

Previous versions of the README.md document how to get the master branch working...
