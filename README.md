# Snatching-Detection-and-Alert-System 
The datset of pictures of snatching event on the road has been used to train the model using the YOLO V8 algorithm.
The ESP32 Camera is connected to the internet to capture the real time images. 
The url of the capture is fed to the model for detection of any snatching incidents.
If found, it is saved to the Google Drive for later use and a Piezo Buzzer connected to the GPIO (output) Pin of ESP32 module goes high to alert the other people nearby. 
