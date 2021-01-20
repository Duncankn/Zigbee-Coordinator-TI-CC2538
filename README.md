# Zigbee-Coordinator-TI-CC2538
A Zigbee coordinator with TI CC2538-CC2592 Zigbee module which is working with Home Assistant System

I am currently having a project applying Home Assistant with Raspberry Pi as an automation lighting system.
There are Zigbee dimmers and Zigbee motion sensors installed in a corridor. The target is that the lights are brightened to 80% when there are people detected; then if there are no people were detected for 1 minute, the lights were dimmed down to 30% in order to save energy.

Due to the environment, the raspberry pi is intalled on the metal grid ceiling. It is not a good environemnt for the Zigbee network, so the Zigbee coordinator cannot be in USB stick form which plugged in the USB port of the Raspberry Pi. Instead, I have take the reference from @egony/MODKAM-STICK-V3 (https://github.com/egony/MODKAM-STICK-V3), and make another Zigbee Coordinator board which is same size as the Raspberry Pi Zero and it will be connected to Raspberry Pi with a micro USB cable.

