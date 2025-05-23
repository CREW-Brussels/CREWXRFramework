# CREW XR Framework 

CREW XR Framework is an Unreal Engine Plugin developed by CREW, that contains basic assets for the development of a multiplayer VR experience, with XR components such as hand tracking, physics, 1st person point of view and so on.

It contains:
- Different components of our Manu Avatar, such as Skeletal Mesh, Mesh, Skeleton, animation sequences, animation blueprint, control rig, IK rig, Physics asset and T pose.
- an XR player for the immersants or performer
- an XR player state

***
Requirements:
- Unreal Engine 5.3
- [Download](https://github.com/CREW-Brussels/CREWXRFramework.git) the plugin's folder in the Plugins folder of your project here or if your project is on git, add this command in the Plugins folder of your project:
```
git add submodule https://github.com/CREW-Brussels/CREWXRFramework.git
```
***

## GOOD TO KNOW
Whenever you'd like to use one of of the components, never modify them directly from the PLUGIN: always create a blueprint inherited from those assets.

## Set up VR with our XR tools 

In order to use our XR settings to launch a new VR experience: 
- make sure it's in play in VR
- Create a GameMode for your VR experience with our assets:

## Decide on the visibility of the first person POV
