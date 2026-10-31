BERMUDA FIRE - UNITY STARTER PROJECT
=====================================

This is a starter Unity project scaffold created from scratch.
It is a playable OFFLINE prototype foundation, not a finished battle-royale game
and not an APK yet.

RECOMMENDED EDITOR:
- Unity 2022.3 LTS (or a compatible newer Unity version)
- Android Build Support, Android SDK & NDK, OpenJDK
- Build target: Android, ARM64, Landscape

IMPORTANT PHONE-ONLY LIMITATION:
Unity Editor does not run natively as a normal Android app. From an Android phone,
you can store/share this project and use a cloud/remote computer with Unity installed
to open it, generate the scene, and build the APK. A Git repository alone does not
compile an APK.

PROJECT SETUP:
1. Extract this ZIP.
2. Open the BermudaFire_Unity_Starter folder in Unity Hub on a computer/cloud PC
   with Unity 2022.3 LTS installed.
3. Wait for scripts to compile.
4. Open Assets/Scenes/BermudaIsland.unity after running:
   Tools > Bermuda Fire > Create Prototype Scene
   (The editor script creates the scene and basic touch UI.)
5. In Build Settings, add Assets/Scenes/BermudaIsland.unity.
6. Switch platform to Android; set Landscape orientation and ARM64.
7. Build an APK.

WHAT IS INCLUDED:
- Third-person CharacterController movement
- Keyboard controls for editor testing
- On-screen virtual joystick
- Jump button
- Follow camera
- Simple island scene generator using built-in primitives
- Basic main menu / restart UI

CONTROLS:
- Android: left virtual joystick to move, JUMP button to jump.
- Editor: WASD / arrow keys to move, Space to jump, mouse to orbit camera.

NOT INCLUDED YET:
Online multiplayer, matchmaking, weapons, combat, vehicles, polished assets,
anti-cheat, backend services, or Play Store release configuration.

Build and test a small prototype first. Keep graphics simple for mobile performance.
