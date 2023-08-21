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

8. Next, got to View<Outputs<Change host, port or message< Change the Host to your IP-adress (for some reason it is localhost by default), then click "OK" and close the OUTPUT window

9. Click on View < Input/output connection editor < See picture below how to connect the inputs

   

​		IPHONE

9. Open the Motion Sender app on your iPhone 
10. Make sure the IP adress matches with the IP from your Computer 
11. Select "Pitch, roll, yaw" and deselect all the other inputs 



