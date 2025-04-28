# solaar_logitech_m720
Set of rules for the Logitech M720 mouse for the program Solaar.

"Solaar is a Linux manager for many Logitech keyboards, mice, and trackpads that connect wirelessly to a USB Unifying, Bolt, Lightspeed, or Nano receiver; connect directly via a USB cable; or connect via Bluetooth."¹
¹ https://pwr-solaar.github.io/Solaar/

This set of rules try to emulate the functioning of the Multiplatform gesture button on the Logitec program for Windows. The gesture functions on the Windows program works as shown on this video (https://www.youtube.com/watch?v=E7YjQ01gacE).

To copy this set or rules you need to replace the rules.yaml on your computer (normally on ~/.config/solaar/rules.yaml) with the file downloaded from here. After replacing the file the rules will appear on the Rule Editor window of Solaar. They will look like this:

![001](https://github.com/user-attachments/assets/f8472b08-dc84-4aa6-89fd-0f52e7a01d4a)
![image](https://github.com/user-attachments/assets/fc79f61c-a736-4913-a87a-5495a709caf8)
![image](https://github.com/user-attachments/assets/98b18c1c-0285-4fc0-a9c7-a295b15a1d2c)

You also can configure it manually, just copy the configurations as shown on the images above.

The first two rules make the left and right buttons of the wheel to Zoom In and Zoom Out. 

The next 3 sections will set all three side buttons on the mouse to the Multiplatform gesture button. 

The second section of rules are the configuration of the Forward Button. First, the program will look for the release of the Forward Button, when this happen it will go through a sequence of 5 checks. The first 4 represents one mouse direction and each one do one action. The last action is the action when the mouse don't move to any direction. 

The third and fourth sections are the configurations of the Back Button and the lowest button.
