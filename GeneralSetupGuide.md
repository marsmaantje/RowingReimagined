# General Setup Guide

**Table of contents**
1. [Launching Softwares]()
    * [SteamVR]()
    * [NeosVR]()
    * [RP3 Interface]()
    * [Websocket Logger]()
2. [Setting Up in Neos]()
    * [Finding and Opening the World]()
    * [Alligning the Real and Virtual Machine]()
    * [Setting up the Virtual Boat]()
    * [Setting the Type of Training]()
3. [Go Rowing]()

## Launching Softwares

### SteamVR
Launch SteamVR through the top bar of your steam application.<br>
![Image of mouse hovering over VR button in Steam](/Images/SteamVRLaunch.png)

### NeosVR
Launch NeosVR from your Steam library.<br>
> **Note**<br>
> When presented with launch options, either pick "Launch Neos VR in Steam VR Mode"<br>
> Or Launch Neos Launcher, and pick Steam VR in the launcher window
> ![Image of Neos Launcher with SteamVR being selected](/Images/NeosVRLauncher.png)

![Image of mouse hovering over play button of Neos](/Images/NeosVRLaunchButton.png)

### RP3 Interface
Launch the RP3 interface.<br>
With the Machine connected to a USB port, click on "Find machine". This will bring up a list of connected USB devices. From this list, the RP3 is usually the on with the highest number, but you will know you selected the correct port if the graph suddenly jumps up.<br>
![Image of RP3 machine selected and graph jumping up]()

### Websocket Logger
Launch the Websocket Logger.<br>
This app is currently not integrated into the rowing world in Neos...

## Setting Up in Neos

### Finding and opening the world
In Neos, open your dash and navigate to the "Inventory" screen. In here you should see a folder titled "Rowing World"
(if you do not see this folder go to the [Getting started with Neos](FirstTimeSetupGuide.md#getting-starter-with-neos) segment of the [First Time Setup Guide](FirstTimeSetupGuide.md))<br>
![Screenshot of empty inventory, with "Rowing World" folder hovered over](/Images/NeosVRInventoryWithFolder.png)<br>
Double click this to open.
In there you should see a world orb, double click this to spawn it out.<br>
![Screenshot of world orb inside the folder](/Images/NeosVROrbInFolder.png)<br>
Now close your dash and double click the world orb in front of your camera to open the world, alternatively you can click once for more options on how you want to open the world.<br>
![Screenshot of world orb, context menu opened on it](/Images/NeosVROrbContextMenu.png)

### Alligning the Real and Virtual Machine
In the world you will be presented with a row of virtual ergometers. Go to any of these and, by using the menu next to it, assign your trackers to the different parts of the ergometer.<br>
![Screenshot of menu, select tracker hovering]()<br>
The menu has three different trackers that need to be assigned, the Machine, Handle ans Seat.<br>
You can assign a tracker by clicking the "Select Tracker" Button on the menu, this will equip a tooltip on your right hand, use this to point to the virtual representation of the correct tracker attached to the rowing machine, if you then press trigger it will select that tracker and the reference in the menu will no longer be <i>null</i>.<br>
![Screenshot of tool equipped on hand, pointing towards tracker]()<br>
![Screenshot of tracker being selected, menu no longer showing null]()

### Setting up the Virtual Boat
After alligning the virtual and real ergometer, you can walk to the boat at the dock. Here you are presented with a menu to generate different lengths of the boat, depending on how many users you want to row with. Input the correct number into the menu and press "Generate" to create a boat with the set amount of places for people to sit.
![Screenshot of Boat menu, with 2 people selected and keyboard open]()

### Setting the Type of Training
Next to the Boat is a second menu to set the type of training you want to do, this can be one of two types:<br>
1. Distance: you set how many "Units" (approx. 1 meter) you want to row.
2. Time: you set how many seconds you want to row.

Once everyone is seated the selected training will begin, and automatically end after the set condition is met.<br>
![Screenshot of Distance selected with 2000m set]()<br>
![Screenshot of Time selected with 240 seconds set]()<br>

## Go Rowing
After setting everything up, simply sit in the seat you chose, and once everyone is seated the training will automatically start.
![Screenshot of start countdown with everyone seated]()