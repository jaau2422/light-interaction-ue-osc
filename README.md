# light-interaction-ue-osc
Repo for OSC + Unreal Engine + Wekinator

(A)<u>*Requirements/Installation guide*</u>

1. Unreal Engine:

   - Unreal Engine Version 5.1

   - OSC Plugin

2. On your Computer:
   - install Wekinator (Windows recommended): wekinator.org/downloads/
3. On your iPhone: Download "Motion Sender" For Wekinator by Louis McCallum



(B) *<u>Set up</u>*

​		UNREAL ENGINE

1. Open project "meetOriginal" with UE 5.1

2. Open Level "Interaction_new"

3. Open Blueprint in the Outliner "BP_OSC_LIGHT"
   ![alt text](https://github.com/jaau2422/light-interaction-ue-osc/blob/main/images/Tutorial_Setup_Blueprint_OSC.png?raw=true)

5. Edit the IP4-adress of the Recieving Server to the IP adress of the Computer that you will send the OSC message from (Make sure "Start Listening is ticked"!)

   

   WEKINATOR

6. Open a new Wekinator project

7. Insert the following Inputs:
   ![WekinatorSetup](https://github.com/jaau2422/light-interaction-ue-osc/blob/main/images/Tutorial_Setup_Wekinator_NewProject.png?raw=true)

9. Next, got to View<Outputs<Change host, port or message< Change the Host to your IP-adress (for some reason it is localhost by default), then click "OK" and close the OUTPUT window

10. Click on View < Input/output connection editor < See picture below how to connect the inputs:
     ![WekinatorSetup](https://github.com/jaau2422/light-interaction-ue-osc/blob/main/images/Tutorial_Setup_ConnectionEditor.png?raw=true)

   

​		IPHONE

9. Open the Motion Sender app on your iPhone 
10. Make sure the IP adress matches with the IP from your Computer 
11. Select "Pitch, roll, yaw" and deselect all the other inputs :





9. ![WekinatorSetup](https://github.com/jaau2422/light-interaction-ue-osc/blob/main/images/Tutorial_Setup_iPhoneSettings.jpg?raw=true)

12. Now you are ready to train your Wekinator Neural network with your phone movement!

<u>(C) *Training you movements in Wekinator*</u>

In this case, the use of Wekinator is basically so we can easily map the values from our phone from a weird float input to a stable 0 - 1 output. The use of the Neural Network here is literally just to smooth out the values! 

What you need to do, is put someone with the phone in front of the LED Wall (App needs to be open and "Send"-toggle "on" all the time during the interaction!) 

Another person sits in front of the Computer dragging the slider of the wekinator input from 0 - 1. While this happens, the light on the LED wall should move from left to right on outputs-1 and from top to bottom with outputs-2.

You should record your inputs starting with the left to right movement. In order to do that, the outputs-2 values shouldnt record. To stop outputs-2 from recording, the red recording button next to it should be clicked to disable it.



