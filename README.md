# tessel-camera
Shoot pictures with your tessel using the config button

## At Hackster
This repo, as simple and straight forward as it is, is also available on Hackster projects : [tessel-camera](https://tessel.hackster.io/theunexpected1/tessel-camera-eca428).

Somehow, it's one of the highest respected #tessel projects at Hackster.

## Requirements
You will need:
* [tessel](https://tessel.io/)
* tessel [camera module](https://tessel.io/modules#module-camera)


## Install

* Clone the repository
* run ````npm install```` to install the tessel camera module
* plug your camera module to the tessel, then connect the tessel to your computer via the cable provided
* run ````tessel run index.js -u ./uploads```` to load the app on the tessel RAM

## Usage

* the orange LED will be ON once the tessel & the camera are ready
* click the `config` button on the tessel to click pictures (blue LED for feedback)