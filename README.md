<!-- boardrepo-badge:v1 -->
[![View on BoardRepo](https://boardrepo.com/badge/github.svg?v=2)](https://boardrepo.com/b/6f306820-acc4-4aef-8e22-920ab4c59a56?ref=github-readme)
<!-- /boardrepo-badge:v1 -->

# ShineAssistant
Your way to solar inverter production data without the cloud-stuff!

## Audience
Owners of Growatt 1-3000-s solar inverters who want to integrate to Home Assistant or other local monitoring solutions, rather than relying on Growatt's cloud services.

## Function
This device extracts loads of runtime data from the growatt inverter and makes it all available in several ways; I'll be focusing on the MQTT-approach.

## What you get
Insight into the life of your solar energy solution. What, how much, when and possibly also a little bit of the 'why'. 
Knowledge is power!  So you get power. It's on you to use it wisely.

## How you get it
### Build the hardware
This is the place for the hardware. Schematics, BOM and all the usual stuff is there for you to poke at. I use KiCAD, and PCBs can be ordered from the gerbers it produces. <https://jlcpcb.com> will readily produce and send the nicest boards at reasonable prices.
### Compile the firmware
Have a look at <https://github.com/mafiltenborg/openinvertergatewaySA> where the fully customized firmware matching the hardware you find here is located. This is not my invention; other smart people have done the heavy lifting, and all I did was tweak and adapt. Still, you'll have to setup camp with PlatformIO and jump through a number of hoops to get at the firmware.
### Print the case
I use OpenSCAD. Luckily, it's free for all, so get cracking and produce .stl-files for your own slicer. You'll likely have to tweak things a bit, as all printers are a little unique.
### And finally
Setup your data extraction scheme as you see fit.

No, I won't sell you a ready made device. I also won't come around and install it. This is DIY, and for obvious reasons DIY-as-a-Service (DIYaaS) does not exist.

## How you use it
That's entirely up to you. Over time, I'll show a couple of examples here, hoping to inspire punters. But like with everything else in this project, it's up to you to assemble the 'virtual LEGO blocks' your own way.