# sound_activated_camera

This project uses the sound input to an Electret Condenser Microphone to trigger an Adafruit camera to snap pictures/video.
If the sound level (measured in voltage) is greater than 2.50, then trigger the camera to snap a picture and save it to an SD Card.

Hardware Used:
1. Weatherproof TTL Serial JPEG Camera with NTSC Video and IR LEDs
2. Electret Microphone Amplifier - MAX4466 with Adjustable Gain
3. MicroSD card breakout board+
4. Arduino Uno

Directions (picture) for camera and sd wiring can befound here: https://learn.adafruit.com/ttl-serial-camera/using-the-camera

Wiring For Microphone:
OUT -> A0
Power -> 3v
Ground -> GND
