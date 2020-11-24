# REPORT / README

The project has been made using ARFoundation library of Unity.

 **Pre Requisites:**
 The following modules must be installed.
 1. Android Build Support
 2. Android SDK and NDK Tools
 3. OpenJDK
 To install the modules, go to Unity Hub, click on the three dots in the relevant Unity Version, click on Add Modules and then from the options select the above three options and click on next.

**Building the APK:** 
1. Open the projec in unity
2. In your mobile, go to settings-> About -> Software Information -> Build Options -> Tap on it severla times (7-10) to enable developer options
3. In developer options, turn on USB Debugging
4. Come back to the open project in Unity, go to File -> Build -> Select your device from the menu -> Build
5. This will build the app on your phone. Then you can run it.
*Note:* It is suggested to use a windows machine to do this as the latest version of Unity Hub in linux is buggy.

**Project Details:**
* Phone Camera sees the environment
* The camera detects planes in the environment (This was done by using AR Plane Manager)
* Once a plane is detected, user can click on the plane to place an object on the plane
* Presently the object is a simple cube. But that can be easily replaced
* The person can move around and view the cube from different angles.