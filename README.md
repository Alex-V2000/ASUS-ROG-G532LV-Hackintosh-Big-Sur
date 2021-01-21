# ASUS-ROG-G532LV-Hackintosh-Big-Sur
Hackintosh OpenCore macOS Big Sur 11.1 on ASUS ROG STRIX SCAR 15-G532LV !

### Only for MacOS Big Sur !
### OpenCore 0.6.5

### Laptop Specifications:
* Processor: Intel Core i7-10875H 2.3GHz (Turbo 5.10GHz)
* Graphics 0: Intel UHD Graphics Comet Lake 1.5GB
* Graphics 1: NVIDIA GeForce RTX 2060 6GB (DISABLED)
* RAM Memory: 16GB DDR4 3200MHz
* SSD: Intel SSDPEKNW512G8
* WI-FI + BT Card: Intel AX201
* Audio Card: Realtek ALC294
* TouchPad: ELAN 1403

![About](https://github.com/Alex-V2000/ASUS-ROG-G532LV-Hackintosh-Big-Sur/blob/main/Screenshots/1.png)

### Working:
* Intel UHD Graphics
* 240Hz Screen
* Keyboard (Hotkeys: Screen Brightness, KB Brightness, Volume)
* Change KB Color
* TouchPad and Gestures
* All USB Ports (3.1 and Type-C)
* CPU Power Management
* Sleep Mode
* iMessage and other Apple services
* Audio ALC294 and Headphones Jack

### Not Working:
* Airdrop
* NumberPad
* HDMI (It is connected to the NVIDIA Card)

### Keyboard Shortcuts and KB Backlight:
* Open `macROGAuraCore` folder.
* On terminal run `chmod +x install.sh`, and execute the script.
* Copy `ROG-HID.app` and `ROGSwitch.app` in `/Applications`.
* Run `ROG-HID.app` and click on 'Activate ROG-HID Extension'.
* Run `ROGSwitch.app`.

### Bugs:
* When the device is turned on directly on macOS, the processor fan will not stop, to solve the problem, first start Windows, and then restart on macOS.
