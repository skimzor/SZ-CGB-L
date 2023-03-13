# SZ Color Lite (SZ-CGB-L) PCB

The SZ Color Lite is a replacement PCB for the Nintendo Game Boy Color. The majority of modders doing a PCB swap will use an IPS-kit to complete their console; by omitting the components that are required for the OEM Game Boy Color screen, the SZ Color Lite PCB makes transplanting from the donor console easier and more efficient. 

# Features

- 4-Layer Board with GND and PWR Planes
- Conveniently-placed solder pads for aftermarket IPS screen kit controls
- Option for tactile buttons on the directional pad, A/B, and start/select buttons (picture below is of an older revision of the PCB)
- Reduced component transfer from donor Game Boy Color console

![](images/pcb_front.JPEG)
![](images/pcb_back.JPEG)

# Disclaimer
You will need to transfer components from a working Game Boy Color for this PCB to work.  Please do not attempt this project if you are inexperienced in soldering; populating this PCB will require desoldering and micro-soldering surface mount components.  You will also need to be able to read/understand the CGB schematics and be able to self-troubleshoot any issues.  I do not take responsibility or accept blame for any damage to your Game Boy Color or for any failed attempts. 

**Note**: There are multiple revisions of the OEM CGB PCBs (CPU-01 through CPU-06).  CGB-CPU revisions 01-05 have slight differences in passive components,  but they *should* be compatible with this PCB.  **CGB-CPU revision 06 is incompatible and cannot be used with this PCB.**  

I have personally tested this PCB and successfully created a working SZ Color Lite using components from an OEM **CGB-CPU-04**. All features have been confirmed as working with the unit that I have created. ***However, I cannot guarantee a fully working unit if you undertake this project as there are too many factors that can cause issues, so please acknowledge this disclaimer and order/use this PCB at your own risk. Unless it is a PCB design issue, I will be providing limited technical support for any issues you may have.***

If you have suggestions to improve or identify issues with the PCB design, please contact me on discord: *skimzor#5078*.

# Purchase and Ordering

The SZ Color Lite PCB will be available for purchase through Ko-fi and Etsy:

- [Ko-fi](https://ko-fi.com/skimzor)
- Etsy *(coming soon)*

You can also order the boards through PCBWay as a shared project (in any color you want):

- PCBWay *(coming soon)*

# PCB Bill of Materials & Assembly

As mentioned above in the disclaimer, assembly of this PCB requires advance soldering experience and ability to self-troubleshoot any issues.

Since this PCB uses the original CGB schematics, you are able to directly transplant components from a donor console to create a working SZ Color Lite.  Components can also be ordered through an electronic components distributor (e.g. digikey, mouser, etc.) and can be found in the Bill of Materials (BOM) unless otherwise noted as required from the donor CGB (e.g. CGB CPU, Crystal, etc.). 

**Note:** Component transfer from a donor Game Boy Color to the SZ-CGB-L PCB is one to one (e.g. C1 from the donor PCB goes to C1 on SZ-CGB-L, R3 from the donor PCB goes to R3 on SZ-CGB-L, etc). Please verify orientation/polarity of components before soldering.

Additionally, not all components from the donor Game Boy Color will be used. The SZ Color Lite can only be used with Game Boy Color IPS screen kits and doesn't need the additional voltage rails that the OEM Game Boy Color screen uses; therefore, components for those rails have been omitted from the SZ Color Lite PCB.

# Additional Parts

In addition to the donor Game Boy Color, you will need the following items to make a functional handheld SZ Color Lite.  You can find all of these parts on Retro Game Repair Shop.  Use the discount code **"discord"** for 10% off your order.

- **Game Boy Color IPS Kit:** As the SZ Color Lite will not work with the OEM CGB LCD, you will need a Game Boy Color IPS Kit.  Any Game Boy Color IPS Kit will work but it is recommended to get a Funnyplaying GBC Laminated IPS Kit. [(Link)](https://retrogamerepairshop.com/collections/funnyplaying-gbc/products/funnyplaying-game-boy-color-2-0-q5-ips-laminated-backlight-kit)
- **Game Boy Color Shell:** It is recommended to get the Funnyplaying Laminated IPS-Ready Game Boy Color shell. You can use any Game Boy Color shell but be prepared to trim it to fit the LCD [(Link)](https://retrogamerepairshop.com/collections/funnyplaying-gbc/products/funnyplaying-game-boy-color-game-q5-ips-ready-shell)
- **Game Boy Color Buttons:** RetroCNC Game Boy Color Buttons are my personal recommendation, but if you want plastic buttons it is recommended to get Funnyplaying ones; however, any Game Boy Color buttons will work [(Link)](https://retrogamerepairshop.com/collections/retrocnc/products/game-boy-color-metal-buttons-by-retrocnc) / [(Link)](https://retrogamerepairshop.com/collections/funnyplaying-gbc/products/funnyplaying-game-boy-color-custom-buttons)
- **Game Boy Color Membranes:** Again, it is recommended to get Funnyplaying Game Boy Color membranes; however, any Game Boy Color membranes will work [(Link)](https://retrogamerepairshop.com/collections/funnyplaying-gbc/products/funnyplaying-game-boy-color-silicone-button-contact-pad-membranes)

# DC Power Board

You are able to use the OEM Game Boy Color DC/DC Regulator Board with the SZ Pocket Color; however, there are modern options suggested below:

- skimzor's SZ-REG *(coming soon)*
- [marshallh's GBPP](https://github.com/marshallh/gbpp)
- [leggomyfroggo's frogulator](https://www.etsy.com/shop/FroggoCustoms?ref=nla_listing_details)

# License

 [![License: CC BY-NC-SA 4.0](https://licensebuttons.net/l/by-nc-sa/4.0/80x15.png)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
 
This project/PCB is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License. ***Under this license, you are not permitted to profit from or commercialize this project.***
