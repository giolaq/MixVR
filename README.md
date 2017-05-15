# MixVR
Sample of Android app Mixed with VR Unity app

This project was created as a sample of the intregation between Unity app and an Android Native Java app.

Home Screen:
<img src="https://github.com/joaobiriba/MixVR/blob/master/Screenshots/home.png" width="400">

Tap the Fab to enter in VR:
<img src="https://github.com/joaobiriba/MixVR/blob/master/Screenshots/enterVR.jpg" width="400">


Play the Maze:
<img src="https://github.com/joaobiriba/MixVR/blob/master/Screenshots/vrmaze.jpg" width="400">

assets directory is where all the Unity magic happens, but beware of the [AndroidManifest.xml](https://github.com/joaobiriba/MixVR/blob/master/app/src/main/AndroidManifest.xml).
We have spawn a separate process for Unity player so that coming back from the Unity game doesn't kill the Android app! :)

Exit VR and back to Android app! :)
<img src="https://github.com/joaobiriba/MixVR/blob/master/Screenshots/exitVR.jpg" width="400">
