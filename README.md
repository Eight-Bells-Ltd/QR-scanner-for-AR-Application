# QR-scanner-for-AR-Application
The developed solution will guide the user towards a solution using automated guidelines, through the scanning of the QR codes created by PPC for each RTU unit. It is designed for ORA-2 smart glasses by Optivent.

ORA-2 specifications

![2023-12-13 09_35_59-Window](https://github.com/Eight-Bells-Ltd/QR-scanner-for-AR-Application/assets/144778142/1e61ee66-1ab0-4545-a9ce-4c7eba9e8076)

Remote connection to the  ORA-2 glasses

1) Install the adb drivers from the link below:
https://adb.clockworkmod.com/

2) Install vysor on the computer from the following link:
https://www.vysor.io/

3) Glasses and computer must be connected to the same network.

4) The glasses are connected with a cable to the computer

5) Usb debugging must be enabled.
a) On the glasses, go to Settings > About device
b) Under the build number we tap it 7 times so that the Developer menu
Options menu to appear
c) Settings > Developer Options > Enable USB Debuggin

6) Open the Vysor and click View Device (red button)

The user needs to grant permission when opening the application for the first time after installation.

In the manifest.xml file in Android Studio (https://developer.android.com/studio), the following permissions need to be added:



![2023-12-13 09_45_27-Window](https://github.com/Eight-Bells-Ltd/QR-scanner-for-AR-Application/assets/144778142/e18d4278-c286-4afe-9a2c-5dd67cabdaec)
