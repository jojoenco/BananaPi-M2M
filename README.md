# BananaPi-M2M
## Bananapi-M2M dietpi with WiFi (NO BL-TOOTH !)


DietPi v8.18.2 build with debian Bullseye  
Debian 5.10.179-1  
Kernal 5.10.0-23-armmp-lpae  

User: root  
PW: dietpi

(WiFi is loaded after boot because if you load it in the start process it hangs) 

### First connect to WiFi:  

Network settings --> WiFi : Available  
Would you like to enable WiFi now?  
<Ok>  
Apply : Save all changes and restart networking  
  
Scan : Scan and configure SSID  

0: [Unused] Select to configure  
Scan	--> select your SSID  

WPA-PSK  
type your password  
<Done>  

Apply : Save all changes and restart networking  
Retry               : Re-run the last command that failed  
  
 Would you like to restart the first run setup and installation?  
<Ok>  

### back in DietPi-Software:  

Install            : Go >> Start installation for selected software  

Fixed!!(Sometimes it hangs at reboot at   :   Starting ifup for wlan0...
         Starting Raise network interfaces..  
then pull the power plug) Fixed!!!!!! (won't hang anymore)
  
### Resize to max SD card:   

on the prompt type:  
dietpi-drive_manager  
select ext4 partition  
Resize          : Maximize the available filesystem size  
reboot  

### setup the rest:  
on the prompt type:  
dietpi-launcher : All the DietPi programs in one place  
dietpi-config   : Feature rich configuration tool for your device  
dietpi-software : Select optimised software for installation  
htop            : Resource monitor  
cpu             : Shows CPU information and stats  


## PRESS RELEASE FOR THE IMAGE FILE !!!
  
 

  
