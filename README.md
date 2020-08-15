# ofxKinect2

Kinect SDK 2.0 wrapper for openFrameworks, Windows 10. It's tested with oF 10.1.

(This is fork of original addon at https://github.com/sadmb/ofxKinect2)

Note: It works with single Kinect 2. You you need use multiple devices, please consider ofxKuKinectV2,
https://github.com/perevalovds/ofxKuKinectV2 

# Installing

1. Download and install Kinect SDK 2.0 from here:  
https://www.microsoft.com/en-us/download/details.aspx

or download KinectSDK-v2.0_1409-Setup.exe file here:
https://cloud.mail.ru/public/56Pe/4zvWgXyvh

2. Add to C++ -> General -> Additional Include Directories: $(KINECTSDK20_DIR)inc;  

3. Add to Linker -> Input -> Additional Dependencies: Kinect20.lib;  

4. (for Win32): add to Linker -> General -> Additional Library Directories: $(KINECTSDK20_DIR)Lib\x86;  

(for x64): add to Linker -> General -> Additional Library Directories: $(KINECTSDK20_DIR)Lib\x64;
