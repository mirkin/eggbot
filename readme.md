
Servos speed too fast so used Ejjduino_ARDUINO/ and added 
VarSpeedServo to save the pen tips.

Didn't detect Arduino so modified eggbot2.8.0
ebb_serial.py
if port[1].startswith("EiBotBoard") or port[1].startswith("Arduino") or port[1].startswith("/dev"):
    


In ~/.config/inkscape/preferences.xml, find

<group
    id="documentoptions"
    state="1" />
and change it by adding coordinatesL

<group
    id="documentoptions"
    x="500"
    y="500"
    state="1" />