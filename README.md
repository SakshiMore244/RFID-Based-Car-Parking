# RFID-Based-Car-Parking
In this project I have interfaced RFID module with Arduino in order to control the gate operation RFID identifies the registered card and turns the servo motor ON or
OFF according to the given condition.
If the identified card is registered than the Arduino will send a command to the servo motor to move its shaft position from 0 degree to 100 degree and hence allow
the vehicle to pass. If the tapped card is not registered then the servo motor doesn’t change its position.
For the system programming, Arduino Uno ide was used due its simplicity.
Programming the hardware part included rfid module and servo motor programming which was comparatively easy due to previous knowledge of interfacing LCD and to use If/else functions.
