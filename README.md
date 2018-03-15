# react-native-environment-installation-guide
Installation guide for windows

- install node
- cmd ---> npm install -g react-native-cli
- Download and install Java JDK
- Download and install Android studio

In Android studio go to:  configure ---> sdk manager
And check the following:

## __SDK Platforms-
Android API 27 - check this if not already checked:
- android SDK Platform 27
Android 6.0 (Marshmallow)
- Google APIs
- Android SDK Platform 23
- Sources for Android 23
- Intel x86 Atom_64 System Image

## __SDK Tools-
- Android SDK Build-Tools
- Android Emulator
- Android SDK Platform-Tools
- Android SDK Tools
- Document for Android SDK
- Intel x86 Emulator Accelerator (HAXM installer)

- Also check this if it is not already checked
-Support Repository

#### Now go to Control Panel -->  System and Security ---> System ---> Advanced system settings ---> Environment Variables

## in the User variables add these: (if their are not already there)
- C:\Users\*******\AppData\Local\Android\Sdk\platform-tools
- C:\Users\*******\AppData\Local\Android\Sdk\tools
(change ******* to your user folder)

## in the System variables add these: (if their are not already there)
- name: _ANDROID_HOME          value: C:\Users\timor\AppData\Local\Android\Sdk
- name: _JAVA_HOME                  value: C:\Program Files\Java\*** your jdk folder ***
:)
#### **Created by timorss
