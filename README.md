# OBS
Settings and preferences for OBS to recreate the streaming setup I have.

## Equipment
- M-Audio M-Track Plus
- Shure SM7b microphone
- Hollyland Lark M1 wireless microphones
- Shure SRH840

## OBS Scenes
Face|Web|Desktop|Camera 2
---|---|---|---|
Mic 1 - Shure SM7b|Mic 1 - Shure SM7b|Mic 1 - Shure SM7b|
Mic 2 - Lark M1 (L2)|Mic 2 - Lark M1 (L2)|Mic 2 - Lark M1 (L2)|Mic 2 - Lark M1 (L2)|
Mic 3 - Lark M1 (R3)|Mic 3 - Lark M1 (R3)|Mic 3 - Lark M1 (R3)|Mic 3 - Lark M1 (R3)|
Cam 1 - DSLR 1|Cam 1 - DSLR 1|Cam 1 - DSLR 1|
||||Cam 2 - DSLR 2
Cam 3 - Webcam|Cam 3 - Webcam|Cam 3 - Webcam|
Blinder - Pikmin Katamari|Blinder - Pikmin Katamari|Blinder - Pikmin Katamari|
Background Image - (Cyberpunk, etc)|Firefox|Desktop|

## Sources
- Blinder
  - Fills the entirety of the screen behind the content maker to block out the visual content on the display at the moment.
  - Current image is the Pikmin Katamari picture.
- Cam 1 - DSLR 1
  - Canon T3i
  - 24mm lens
  - Camera rests on a tripod behind the right display monitor. This is the primary camera for displaying the content maker. Camera is connected to the PC using a mini-USB-to-USB-A connector. Canon EOSCAM driver software is installed, but it is not loaded each time OBS is loaded. The DSLR camera is configured in OBS as being of the device EOS Webcam Utility, not requiring to choose the Pro option of the software. Camera is powered by battery power, but a cable has been ordered to power it from AC power. The camera is using default settings, shooting in Automatic mode, the Autofocus was set to establish the proper focal length, and then the camera was set to a manual focus. The subject is illuminated by external lights that provide ample light to not require a poor exposure setting on the camera.
- Cam 2 - DSLR 2
  - Canon T3i
  - Variable lens; 18-55mm lens likely
  - Camera rests on a tripod and is mobile. This camera is the secondary camera for events that are not taking place at the desktop. This camera is still connected to the PC using a mini-USB-to-USB-A connector.  Canon EOSCAM driver software is installed, but it is not loaded each time OBS is loaded. The DSLR camera is configured in OBS as being of the device EOS Webcam Utility, not requiring to choose the Pro option of the software. Camera is powered by battery power, but a cable has been ordered to power it from AC power. The camera is using default settings, shooting in Automatic mode, the Autofocus was set to establish the proper focal length. Subjects should ideally be externally lit, but this is not always an option.
  - Note: This camera requires the use of the Hollyland Lark M1 wireless microphones that are already paired with the appropriate Camera 2 Scene in OBS.
- Cam 3 - Webcam
  - Logitech C920 webcam
  - Camera rests on top of the rightside display monitor. This camera is the backup camera for displaying the content maker. Camera is connected to the PC using a USB cable that is built into the camera. No additional software is installed aside from the drivers the webcam has prebuilt in. Ideally, the subject is externally lit, but as this is a backup camera, there are no expectations. Use this camera if the primary camera fails in the middle of a performance.
- Mic 1 - Shure SM7b
  - Shure SM7b
  - Primary microphone connected to the M-Audio M-Track Plus audio interface, which connects to the PC using a USB-A-to-USB-B connector. The M-Audio M-Track Plus interface required the installation of a driver, but it is not loaded with OBS each time OBS loads.
  - The interface is configured, so that the gain knob on the interface is turned all the way up; the monitor dial is turned to entirely USB; the headphone dial is turned all the way up; the main level is very high; it is set to mono mode on the interface; it is not set to phantom power on the interface; XLR input is set to microphone, not guitar.
  - In OBS, the microphone is configured as a mono input as well. It is equally balanced between the two speakers. There is an audio filter applied in OBS called Noise Suppression. This is set to the Speex method, which is the low CPU usage option, and a Suppression Level of -33dB.
- Mic 2 - Lark M1 (L2)
  - Hollyland Lark M1
  - This is one of the two wireless Lark M1 transceiver microphones. The Hollyland Lark M1 receiver is connected to the PC using a 3.5mm-to-3.5mm connector connected into the 3.5mm microphone input on the motherboard of the PC. This microphone is stored on the left side of the case normally and is indicated on the microphone with L2. This microphone is part of a pair that shares the same receiver. Within OBS, in the Settings, then Audio tab, then Global Audio Devices, Mic/Aux Audio 3 and Mic/Aux Audio 4 were both selected to be the same audio interface from the motherboard (High Definition Audio Device on the current PC); this replicates the receiver across both channels so they can be separated. In the Audio Mixer in the main OBS screen, the three dots menu, and then selecting Advanced Audio Properties, speaking into one of the microphones at a time, I was able to isolate one microphone to the left channel and one to the right channel. L2 goes with the Mic 2.
- Mic 3 - Lark M1 (R3)
  - Hollyland Lark M1
  - This is one of the two wireless Lark M1 transceiver microphones. The Hollyland Lark M1 receiver is connected to the PC using a 3.5mm-to-3.5mm connector connected into the 3.5mm microphone input on the motherboard of the PC. This microphone is stored on the right side of the case normally and is indicated on the microphone with R3. This microphone is part of a pair that shares the same receiver. Within OBS, in the Settings, then Audio tab, then Global Audio Devices, Mic/Aux Audio 3 and Mic/Aux Audio 4 were both selected to be the same audio interface from the motherboard (High Definition Audio Device on the current PC); this replicates the receiver across both channels so they can be separated. In the Audio Mixer in the main OBS screen, the three dots menu, and then selecting Advanced Audio Properties, speaking into one of the microphones at a time, I was able to isolate one microphone to the left channel and one to the right channel. R3 goes with the Mic 3.
