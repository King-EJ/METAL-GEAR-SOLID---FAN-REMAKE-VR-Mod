# METAL-GEAR-SOLID---FAN-REMAKE-VR-Mod
VR Mod METAL GEAR SOLID - FAN REMAKE "Quick VR Mod"


METAL GEAR SOLID - FAN REMAKE VR  -  VR mod (Unity 2022.3, URP, Mono x64, BepInEx 5)
====================================================================================

Version 0.1.1 (test build on Quest 3 VDXR).

WHAT IT DOES
------------
* Stereo VR through OpenXR (SteamVR, Meta/Oculus Link, Virtual Desktop, WMR...).
* First person: your eyes are at Snake's head (his head and body are hidden). The left stick walks where you
  look, the right stick snap-turns.
* Third person: Follow = you float behind him (the right stick turns you around him), or GameCamera = you sit at
  the game's own camera. Switch first / third person: hold the RIGHT GRIP and CLICK the RIGHT STICK.
* 6DOF weapon (first person): the weapon in Snake's right hand sits in your right controller. The game's shots are
  turned to start at its muzzle and go where it points.
* Laser on the weapon while you aim (right grip). In third person it comes out of the gun in his hand.
* Cutscenes / scripted cameras: you sit where the game's camera is.
* The VR controllers are an Xbox controller for the game. Menus and HUD are on a screen floating in front of you.

INSTALL
-------
1. unzip into game folder.
2. Start your VR runtime first, then the game.

CONTROLS (the game's gamepad layout)
------------------------------------
Right trigger ......... attack / fire (RT)

Right grip ............ aim (LT) + laser

A ..................... A (menus: confirm)

B ..................... crouch

X ..................... reload    

Y ..................... action

Left grip ............. item inventory (LB)  

Left trigger .......... weapon inventory (RB)

Left stick click ...... run (L3)  

Right stick click ..... scope (R3)

Right stick left/right  snap turn   

Right stick up / down . d-pad up / down

Left grip + right stick left / right ......... d-pad left / right

X + Y together ........ pause (Start) 

A + B together ........ codec (Back)

Right grip + right stick click ............... first / third person

Both stick clicks ..... re-centre

Both stick clicks held 1.7 s (weapon in hand) . move the weapon in your hand (hold the left grip to grab it,
                                               right stick up / down = size, B = default, A = save)
Both grips held 1.7 s . move the laser start point / direction (A = save)

Y + left stick click held 1.7 s ............. VR settings menu

SETTINGS
--------
BepInEx\config\mgs.fanremake.vr.cfg (saved changes apply while the game runs).
  [View]    View, ThirdPersonStyle, ThirdPersonDistance / Height, HideHead, CutsceneDistance ...
  
  [Aiming]  WeaponInHand, RedirectShots, LaserSight, HideBodyInFirstPerson, WeaponNames, WeaponForwardAxis
  
  [Controls] every gamepad button's VR control
  
  [Camera]  RenderScale, PostProcessing, WorldScale, EyeHeightOffset ...
  
  [UI]      VR screen position / size / drawing

THIS IS A FIRST TEST BUILD
--------------------------
Very janky 
