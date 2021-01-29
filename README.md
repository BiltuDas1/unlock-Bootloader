# Unlock Bootloader
Unlock bootloader into your Android Phone for installing Custom Roms.  

**Warning ⚠️ : By unlocking bootloader, Your Android Phone warranty will be void.**. 

# How to do?  
You can unlock bootloader using your Computer or any other Android Phone (Which supports OTG).  

### Pre-Requesting  
1. A Windows Computer *[PC]*  
2. Android Phone (Which will use for unlocking bootloader) *[MOB]*  
3. A USB cable
4. Little knowledge about Computers*

### How To do using Computer?  

**Note : By using this method your Device will be factory reset, So take a backup of your Personal files.**

**HOST = The Computer**  
**MOB  = Which Device will be used for unlocking bootloader.**  

1. Download ADB & Fastboot, and your Phone Driver.  
2. [PC] Keep all ADB & Fastboot files into a folder.  
3. [PC] Install The Device Driver.  
4. [PC] Hold the **Shift Key** and Right click on the Windows Explorer, Click on the **Open Command Window Here**  
5. Now Connect your Android Device to your Computer using a USB cable.  
6. [PC] Now type **ADB Devices** into the command Window.  
7. [MOB] Now you need to confirm the USB connection.  
8. [PC] If you see your Device code into the command window, It means the device is ready to use. If your Device is not listened there then check your Cable or Device Driver.  
9. [PC] If your device is ready to use then type the below commands into the command window.  
**ADB reboot bootloader**
**Fastboot flashing unlock**
**fastboot reboot**

10. Now your Device will be started by factory resetting with unlocked bootloader.  
