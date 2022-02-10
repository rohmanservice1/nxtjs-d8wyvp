ReadME.txt
Please run InstallDriver.exe first, then plug in USB.
InstallDriver.exe will install these drivers for Windows 98SE/ME/2000/XP/Vista:
Windows 98/ME/2000/XP/Vista: MTK62XX USB Com Port Driver
Windows 98: Mass Storage Driver

Notes:
1. "2K_XP_COM, Vista, 98_MASS, 98ME_COM" dirs and installer.dll must be put in the same direcotry of InstallDriver.exe
2. To run InstallDriver without GUI windows, use "InstallDriver -a".
3. Customers can customize usb2ser_XXX.inf file.
   There is a string in the file:
   MTK6218 = "USB Modem Driver" 
   You can modify it for your product name, for example:
   MTK6218 = "MY_PRODUCT Modem Driver"

[v1.0812]
     [New Feature]
     1.Pass WHQL certification for Windows XP 32 bit

[v1.0821]
     [New Feature]
     1.Support Windows XP 64 bit 
 
[v1.0830]
     [Bug Fix]
      1.Remove the entry refering "V.42bis", since none of our modem supports this protocol

[v1.0845]
     [New Feature]
     1. Pass WHQL certification for Windows Vista 32 bit
     2. Pass WHQL certification for Windows Vista 64 bit


