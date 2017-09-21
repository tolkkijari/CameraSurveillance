# DIY open-source remote camera surveillance system

## 1 Info
The purpose of this project is offer a cheap DIY camera surveillance system. The camera detects movement and sends photos about the movement to the server, which combines a video about them and sends the video and photos to the mobile client.

## 2 Physical requirements
* Raspberry Pi 3 model B (seriously, image processing needs a lots of power)
* Camera Module 2 with long enough attachment cable
* Server with "enough" hard drive space (mine is Debian)
* Android 6.0 or greater mobile device (possible works with lower version, not tested)

## 3 Programmatical requirements
### Rpi
* Node.js v7.7.1 =<
* Default Debian OS
* OpenCV and RaspiCam are needed to install separately (see RpiCam readme)
### Server
* Node.js v7.7.1 =<
### Android
* Android Studio + needed SDKs (for development purposes)

## 4 The future
I'm developing the project just for fun now and then. Next big things will 
* a good documentation 
* finishing the Android App (propably offer a working notification system with Google Firebase)
* offer a multiple camera support (if possible)
* research if is possible attach a wireless USB modem to Rpi
* Rpi using only RAM memory (no SD card burdened) while sniffing movement
* Move URLs to config -file (now they are hardcoded)
* Add identifications for net interfaces

If you find out some bugs, issues or you have some ideas, please raise an issue, or send a pull request.

## 5 License
MIT
