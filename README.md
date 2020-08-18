# better-linear-dialogue-system
Dialogue system which is quick to set up and has a little flexibility

Dialogue setup:

Create a conversation (a scriptableobject asset).
Create a GameObject and attach an NPC script to it. To have more control over what the NPC can do, make an individual script and let it inherit from NPC class.
Create Dialogue UI for the NPC.
Give the NPC everything the inspector asks for.

Notes: 
By default, simply pressing 'E' initiates dialogue. Change this by contextually changing the 'canTalk' variable in your NPC's script.
To change which button triggers interaction, modify the Input Actions asset found in the Input folder.
