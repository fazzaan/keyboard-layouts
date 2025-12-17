Check for latest release version on [Releases page](https://github.com/fazzaan/keyboard-layouts/releases).  

Check for latest builds in [Layout - EN-UK - IPA](https://github.com/fazzaan/keyboard-layouts/blob/main/Layout%20-%20EN-UK%20-%20IPA/) folder.  

## Latest version is 14.3.
Download version 14.3 source files from [Layout - EN-UK - IPA](https://github.com/fazzaan/keyboard-layouts/blob/main/Layout%20-%20EN-UK%20-%20IPA/) folder -- you will have to install them manually because idk how to build a local installer for Linux, and I don't use Windows currently so I can't build the Windows version with MSKLC (only runs on Windows).  

Download [version 14.0 from Releases page](https://github.com/fazzaan/keyboard-layouts/releases/tag/EngIPAv14) (Windows only).
View [ReadMe for version 14.0](https://github.com/fazzaan/keyboard-layouts/blob/main/Layout%20-%20EN-UK%20-%20IPA/ukaddi14/README.md).

_Images are slightly out of date._
_Layouts are not perfectly identical between Windows and Linux._
### `AltGr` layer
![UK14 0 AltGr](https://github.com/user-attachments/assets/3a4ea0b5-4947-43ae-a111-2dd2a7f40c49)

### `AltGr`+`Shift` layer
![UK14 0 ShftAltGr](https://github.com/user-attachments/assets/3601438b-fbe6-4b78-a60c-36a30e73c61c)

_Keyboard layout image is of version 13.0. Version 14.0 will be added soon._  
![keyboard layout pretty deadkeys](https://github.com/user-attachments/assets/3600758e-01a1-49ca-8228-d58f14fb1bfb)

# Installation
## Linux
**For XKB layouts on Linux**

Don't use the "install-system.sh" script, because this will install it into your root operating system.  

Just install them manually into your home .config folder:  

* Go to ~/.config/

* Create xkb folder

* Inside, create symbols folder and rules folder

* Copy the layout file from this github symbols folder into your symbols folder

* In the rules folder, create or update the evdev.xml file.  
You can find info online about how to do that, or wait a bit and I'll add a guide to the main page.

## Windows
* Download the .klc file from the [latest source folder](https://github.com/fazzaan/keyboard-layouts/blob/main/Layout%20-%20EN-UK%20-%20IPA/latest).  
* Open it in [MSKLC](https://www.microsoft.com/en-us/download/details.aspx?id=102134).  
* Check that the keys are as you wish -- you are able to customise them inside the MSKLC app.  
* Build the keyboard layout installation files using MSKLC.  
* Open the export directory and install the layout.  
