***Hand Gesture Control***

## FEATURES

-Sending remote controls to the Tello drone without the use of any controller.
-Using a hand-tracking module to code your hand gestures to control the Tello drone

## INSTALLATION:

***IDE***

-Pycharm Community Edition.

***Packages installed***

-Mediapipe.

-cvzone library.

-Opencv-python.

-Tellopy.

-Pillow.

***Components***

-DJI Tello drone


***HOW IT WORKS***

- Firstly, by using the Tellopy library you can enable the drone and send the remote controls to it by connecting your WLAN to the DJI Tello drone.
- Important functions that should be enabled on the Tello drone are the stream functions, which enable you to use the live feed camera on the Tello for Hand detection and Face  detection using media-pipe and the cvzone library.
- The drone detects the face and creates a box that covers all the features that identify as face features(*in simple terms*), it  also detects the hand and fingers.
- For safety, your hand needs to be closer to your face, so a field(Box) is created closer to your face, and the hand gestures that will send the remote controls to the drone are done in that field.
- Before sending remote controls to the Tello, your fingers are stored as arrays, and a specific array is encoded with its own unique instruction that is transmitted to the drone as remote controls.
- To activate the drone for movement the distance between your left and right hands needs to be close to your shoulders making a cross sign.


