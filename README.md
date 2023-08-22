

![alt text](https://github.com/jaau2422/light-interaction-ue-osc/blob/main/images/Screenshot0.png?raw=true)

# light-interaction-ue-osc
Repo for OSC + Unreal Engine + Wekinator

(A)<u>*Requirements/Installation guide*</u>

<h3>1. UNREAL ENGINE<h3>

   - Unreal Engine Version 5.1

   - OSC Plugin
     
<h3>2. IPHONE<h3> 
   - Download "Motion Sender" For Wekinator by Louis McCallum



(B) *<u>Set up</u>*

​		UNREAL ENGINE

1. Open project "meetOriginal" with UE 5.1

2. Open Level "L_VP_Interaction_new"

3. Open Blueprint in the Outliner "BP_OSC_LIGHT"
   ![alt text](https://github.com/jaau2422/light-interaction-ue-osc/blob/main/images/Screenshot1.png?raw=true)

5. Edit the IP4-adress of the Recieving Server to the IP adress of the machine youre running the project on (Make sure "Start Listening is ticked"!)

   
		IPHONE

9. Open the Motion Sender app on your iPhone 
10. Make sure the IP adress matches with the IP from your Computer and the Port is 6448
11. Select "Pitch, roll, yaw" and deselect all the other inputs :


9. ![WekinatorSetup](https://github.com/jaau2422/light-interaction-ue-osc/blob/main/images/Tutorial_Setup_iPhoneSettings.jpg?raw=true)


(C)  *<u>Test the interaction</u>*

1. Run the Level
2. Make sure your IPhone Screen is on and the App is running. There should be a green Circle next to "Reconnect"
3. Test the Pitch and Yaw movement on your phone and see if the light in the scene is moving. (The Inputs are different from each phone so you might have to turn you phone around a bit)
