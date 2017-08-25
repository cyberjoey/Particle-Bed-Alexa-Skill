# Particle-Bed-Alexa-Skill
This repository contains code and instruction for using the Particle Bed Alexa Skill.

## Hardware Setup

To get the skill setup properly, you will need a Particle Photon IoT microcontroller and a 30 LED NeoPixel strip from AdaFruit. Once you have both of these things, follow the steps below to get hardware setup.
1. Make sure your particle board is setup with your Particle.io account. If you haven't already done so, follow this link for help [Getting Started](https://docs.particle.io/guide/getting-started/start/photon/).
2. After your Photon is setup and powered via USB, you will need to connect the NeoPixel strip to the correct pins. For help on the basic connections of a NeoPixel LED strip refer to [this link.](https://learn.adafruit.com/adafruit-neopixel-uberguide/basic-connections)
	* Connect the data line of the NeoPixels to pin D2 on the Photon.
	* Connect the +5V pin on the NeoPixels to the 3v3 pin on the Photon
	* Connect the GND pin on the NeoPixels to the GND pin on the Photon
3. Open the Particle Dev IDE and make sure your Photon is detected and selected in the list of devices in the toolstrip on the bottom of the IDE.
4. Open the *.ino file in this GitHub repo and click the lightning bolt icon in the left panel to compile and flash the Photon. For more help getting your device selected and flashing the photon.
5. Your done! Try saying: "Alexa, tell Particle Light to turn on" 
