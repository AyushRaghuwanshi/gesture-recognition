# gesture-recognition
Developed a Gesture Recognition System (combination of face , eyes and hands ) and used it to control the media player on my computer.
<br>
* In this i have used opencv to take input from the camera= and harcasscade features to detect face , eyes , and closed palm . <br>
* hotkeys implemented till now = <br>
  * if you try to look here and there or your face goes out of the frame than video will stop and resume from there where you left when your face comes into the frame .<br>
  * if you bring your right close palm than volume will be increased .
  * if you bring your left palm than volume will be decreased.
  * if you close eyes more than 2 second than video should be paused.
  
<br> code hints =
* used x coordiante of face cascade classified to differentiate between right closed palm and left closed palm.
* used keyboard library to press hotkeys of vlc media player by code.
