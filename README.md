# Unlock Bootloader
Unlock bootloader into your Android Phone for installing Custom Roms.  

**Warning ⚠️ : By unlocking bootloader, Your Android Phone warranty will be void.**  

# How to do?  
You can unlock bootloader using Windows-Android or Android-Android method (Requires OTG).  

### Pre-Requesting  
1. A Windows Computer *[PC]*  
2. Android Phone (Which will use for unlocking bootloader) *[MOB]*  
3. A USB cable  
4. Little knowledge about Computers*

**Note : By using this method your Device will be factory reset, So take a backup of your Personal files before unlocking bootloader.**  

### How To do using a Windows Computer? (Windows-Android)  

**PC = A Windows Computer**  
**MOB  = Which Device will be used for unlocking bootloader.**  

1. Download ADB & Fastboot, and your Phone Driver.  
2. [PC] Keep all ADB & Fastboot files into a folder.  
3. [PC] Install The Device Driver.  
4. [PC] Hold the **Shift Key** and Right click on the Folder, Click on the **Open Command Window Here**  
5. [MOB] Goto your Device **Settings > About Phone > Build Number** and press it about 7 times. Then find out into your Phone **Development Options** and turn on **USB Debugging**.  

![Turning on the ADB USB Debugging in Developer Options](https://github.com/BiltuDas1/unlock-Bootloader/blob/main/Images/IMG_20210129_150703_465.jpg?raw=true) 

5. Now Connect your Android Device to your Computer using a USB cable.  
6. [PC] Now type **ADB Devices** into the command Window.  
7. [MOB] Now you need to confirm the USB connection.  
8. [PC] If you see your Device code into the command window, It means the device is ready to use. If your Device is not listened there then check your Cable or Device Driver.  
9. [PC] If your device is ready to use then type the below commands into the command window.  
**ADB reboot bootloader**  
**Fastboot flashing unlock**  
**fastboot reboot**  

10. Now your Device will be started by factory resetting with unlocked bootloader.  


### Error while unlocking bootloader
Sometimes you may be fail to unlock bootloader into your Android Device due to Driver error (Or any other reason), Or you has not any PC to unlock bootloader. Then you can use the Android-Android method to unlock bootloader. Just you need another Android Device to perform this operation. The Android Device will be work like a PC, and It no need any Root Permission.  

features:  
1. No need any PC  
2. No need any Root Privilege  
3. No need to install any driver  
4. Just install an App to do whole operation  

### Pre-Requesting  
1. An Android Phone (will be used instead of PC) *[HOST]*  
2. Android Phone (Which will used for unlocking bootloader) *[MOB]*  
3. An OTG  
4. A working mind 🧠 ¦)  

### How to unlock bootloader using an Android Phone? (Android-Android)

**HOST = An Android Phone**  
**MOB  = Which Device will be used for unlocking bootloader.**  

1. [HOST] Download Bugjaeger.apk file and install it.  
2. [MOB] Goto your Device **Settings > About Phone > Build Number** and press it about 7 times. Then find out into your Phone **Development Options** and turn on **USB Debugging**.  
3. Now Connect your Android Device (HOST) to your another Android Device (MOB) using an OTG.  
4. [HOST] If the OTG connected successfully then Bugjaeger will be opened automatically.  
5. [HOST] In Bugjaeger, goto the **Command** Section, and then click on the **Reboot Bootloader**.  

![Command Section, Bugjaeger](https://github.com/BiltuDas1/unlock-Bootloader/blob/main/Images/Screenshot_20210129-153440_Bugjaeger.jpg?raw=true)

6. [HOST] While the device is opening into bootloader then another confirmation box may come there. Confirm it.  

![Device Connected Bugjaeger](https://github.com/BiltuDas1/unlock-Bootloader/blob/main/Images/Screenshot_20210129-142700_Bugjaeger.jpg?raw=true)

7. [HOST] When your Android Device is boot into FastBoot mode, goto in the **Fastboot** section and click on the **Command** button, It will open a command window.  

![Fastboot Section, Bugjaeger](https://github.com/BiltuDas1/unlock-Bootloader/blob/main/Images/Screenshot_20210129-153445_Bugjaeger.jpg?raw=true)

8. [HOST] Now type **ADB Devices** into the command Window.  

![Fastboot Shell, Bugjaeger](https://github.com/BiltuDas1/unlock-Bootloader/blob/main/Images/Screenshot_20210129-154836_Bugjaeger.jpg?raw=true)

9. [HOST] If you see your Device code into the command window, It means the device is ready to use. If your Device is not listened there then check your Cable or OTG.  
10. [HOST] If your device is ready to use then type the below commands.  

**Fastboot flashing unlock**  
**fastboot reboot**  

10. Now your Device's Bootloader is unlocked.  