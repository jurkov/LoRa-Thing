# Nano Sensor Node
(C) Jurkov copied from https://github.com/things4u/LoRa-Thing

This sketch is for a LoRa sensor node based on the Arduino Due MCU and a RFM transceiver.
As the node will only transmit its values once every 3 minutes or so, and need to be operated
on batteries, we will disable the receiver functions for this node so and sleep between transmissions.

So the Node does not read messages and it will be single channel also.

Although its messages will be read and received by a LoRa gateway, it will nto implement
any advanced funtions.

June 2016