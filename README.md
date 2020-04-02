
AnimationAdaptation is the Unity software described in the thesis. It does not have a proper build and needs to be
started from within the Unity editor. This made switching between the normal and random versions of the system easier during testing.
The project already contains the necessary .json files so the C# program does not to be started beforehand.  
 The project was created with Unity 2017.4.37f1. Some newer versions may have issues with opening the project because some files are not supported anymore, like TextMeshPro.   

----------------------------------------------------------------------------------------------------------------------------

To run the emotion analysis version:

In "SpeechBubbleCanvas" check the "Dialogue Handler" and uncheck "Dialogue Handler RANDOM_EMOTION" script  
In "VRTKScripts" -> "RightController" check the "VR Listener" script and uncheck the "VR Listener RANDOM Dialogue" script.

----------------------------------------------------------------------------------------------------------------------------

To run the random version:

In "SpeechBubbleCanvas" check the "Dialogue Handler RANDOM_EMOTION" and uncheck "Dialogue Handler" script  
In VRTKScripts -> RightController check the "VR Listener RANDOM Dialogue" script and uncheck the "VR Listener" script.

----------------------------------------------------------------------------------------------------------------------------

It is recommended to use an HTC Vive to start the software with.

CONTROLS (HTC Vive):

Trackpad: press for teleportation  
Trigger: press for button click  
Left grip button: press for dialogue progression when the curtain has opened  
Enter: opening the curtain when prompted   

----------------------------------------------------------------------------------------------------------------------------

CONTROLS (Keyboard and mouse)

Most instructions how the controls are mapped are shown on screen but the following interactions are the most important ones:

WASD: Movement  
Left Mouse Button: press for dialogue progression when the curtain has opened  
Right Mouse Button: press for button click  
Enter: opening the curtain when prompted  
