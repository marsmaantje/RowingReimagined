# First Time Setup Guide

**Table of contents**<br>
1. [Hardware Installations](#hardware-installations)
    * [Requirements](#requirements)
    * [Setting up VR](#setting-up-vr)
    * [Setting up the RP3](#setting-up-the-rp3)
    * [Setting up the trackers](#setting-up-the-trackers)
2. [Software Installations](#software-installations)
    * [Steam](#steam)
    * [SteamVR](#steamvr)
    * [NeosVR](#neosvr)
    * [RP3 Interface](#rp3-interface)
    * [Websocket Logger](#websocket-logger)
3. [Startup](#startup)
    * [Getting started with Neos](#getting-starter-with-neos)
4. [General setup](#general-setup)

## Hardware Installations

### Requirements
For this setup the following hardware is required (per machine/user):
* (1x) VR Capable PC<br>
Recommended specs:
    * CPU: Fast
    * Memory: 16GB minimum
    * Graphics: RTX 2070 or better
    * Storage: 10GB available
    * (note the correct video output for the VR headset)
* (1x) VR Headset<br>
    * Basestation tracked device required<br>
    eg. Valve Index, HTC Vive (Pro / Pro eye)
* (3x) VR Trackers<br>
    * Tundra trackers recommended<br>
    (makes attaching one to the handle easier)
* (1x) RP3
* (1x) Mini USB to USB A cable (3 meter minimum length recommended)
* (Optional) Double sided tape (for fixing the trackers to the machine)

### Setting up VR
A minimum Play Space of 2.5m wide and 4.5m long is recommended for one machine, in addition to space for the computer, monitor, etc.<br>
> **Note**<br>
> This width is for one rowing machine,<br>
> Add 1.5m to the width for every additional rowing machine<br>

![Image of Playspace drawing containing 2 rowing machines]()

Setup the BaseStations (of wich you probably have two) in opposite corners in the room. Place them as high as you can get them, looking down on the Play Space, so that there is line of sight to at least one of the stations from any point in the Space.<br>
![Image of Basestations in the corner of a playspace](/Images/BasestationCorner.jpg)

### Setting up the RP3
Place the RP3 in the middle of your playspace, it is recommended to have the machine side facing the computers so the connecting cable doesnt tangle.<br>
![Image of RP3 in the playspace, with cable connected to computer](/Images/ConnectedRP3.jpg)

### Setting up the trackers
Place the trackers on the RP3
<br>TODO: make placement a bit more descriptive, where does each tracker need to be placed.<br>
> **Note**<br>
> An adapter has been designer for the tundra tracker to attach it to the handle easier. The model to 3D print can be found [here](link to 3d model)
<br>

![Image of the machine tracker placed on the RP3](/Images/MachineTracker.jpg)<br>
![Image of the Handle tracker placed on the RP3](/Images/HandleTracker1.jpg)<br>
![Image of the Handle tracker placed on the RP3](/Images/HandleTracker2.jpg)<br>
![Image of the Seat tracker placed on the RP3](/Images/SeatTracker1.jpg)
![Image of the Seat tracker placed on the RP3](/Images/SeatTracker2.jpg)

## Software Installations

### Steam
1. [Download](https://store.steampowered.com/about/) and run the steam installer.
2. Follow the installation instructions.
3. Login to an existing steam account or make a new one.

### SteamVR
In steam:
1. Search for "steamVR" on the store.<br>
![Image of steam search page with steamVR as first result](/Images/SteamVRSearch.png)
2. Download steamVR.<br>
![Image of mouse hovering over download button on steamVR store page](/Images/SteamVRInstall.png)
3. Run steamVR and follow the first time setup guide.<br>
![Image of mouse hovering over play button of steamVR](/Images/SteamVRLaunch.png)<br>
![Image of first screen of the setup guide](/Images/SteamVRSetup.png)

### NeosVR
In steam:
1. Search for "NeosVR" on the store.<br>
![Image of steam search page with NeosVR as first result](/Images/NeosVRSearch.png)
2. Download NeosVR.<br>
![Image of mouse hovering over download button on NeosVR store page](/Images/NeosVRInstall.png)
3. Run NeosVR and follow the first time setup guide.<br>
![Image of mouse hovering over play button of NeosVR](/Images/NeosVRLauncher.png)<br>
![Image of first screen of the setup guide](/Images/NeosVRLaunchFirstTime.png)

### RP3 Interface
The RP3 Interface is hosted in [this repository](), you can go there and download and build the application yourself, or download the latest build [here]().

### Websocket Logger
The Websocket Logger is hosted in [this repository](), you can go there and download and build the application yourself, or download the latest build [here]().

## Startup

### Getting starter with Neos
If it is your first time running NeosVR, you will be prompted to make an account and follow the first time user guide, it is highly recommended to follow this short tutorial on how to do simple interactions in Neos and not just skip over it.<br>
If you want to go back to the tutorial on a later date you can open the world again through your dash<br>
![Image of laser hovering over tutorial world option in dash](/Images/NeosVRTutorialWorld.png)<br>
A list of tutorials, ranging from the very basics to very advanced topics can be found [here](https://wiki.neos.com/Tutorials).

In your Inventory, if it does not contain a folder labeled "Rowing World", paste this link into Neos:<br>
`neosrec:///G-UT-Mixed-Reality/R-0e22c94a-40ff-48a2-ace5-f53ed2d1d78e`<br>
This will spawn a folder in front of your camera which you can save to your inventory.

## General Setup
Congratulations you have done everything required to setup the VR environment for use.<br>
The general setup on how to open the world and get rowing can be found [here](GeneralSetupGuide.md)