# Simple_USB_and_RJ45_cabeltester
A simple cabel tester for USB-A;USB-C;Micro-UBS;USB-B;RJ45


DISCLAIMER: This is a work in progress project. Please do not be suprised to find errors, and if please leave me some feedback so I can fix it ASAP.
I will be ordering the first batch in the coming days for testing. If you choose to build this PCB yourself, you do so at your own risk. 

<b/>
I am not liable for any damage to property or injury that may result from using this design.


</b>


This is a little cabele tester.
It´s desinged  to test wether a conection, via a Conductor, is present or not.
You can use it to identify Broken/cheap cabel.


------------------------------------
Cable Tester v1.0
Instructions:

Plug one end into Side A
and the other into Side B

Power the device via the
POWER Micro-USB port.

Press the TEST switch.

If an LED lights up, that lane
allows current to pass.

https://github.com/dasistcrafter
------------------------------------
DO NOT PLUG INTO ANY DEVICE!
IT CAN KILL IT INSTANTLY!

the text above can also be found printet on the PCB.


It works by applying 2 volt on site A.
The power is the transmitted over the cabel.
If the string inside the cabel is broken the led should not light up.
There can be false OK results becase 2 Conductors are touching inside the wire.I
If this is the case the current desing can not detect this.
(I am planig a version with a miocrocontorler in the future that can detect these kinds of malfunctions)

If you dont want to keep pressing the button you can conect the holes by the RJ45_A conector.(This can lead to more stress on the cabel and is not recommend)


![image](https://github.com/user-attachments/assets/a8cd5e70-08a2-4346-809a-5d523769f88b)

Note: You can get the files from me if you want. I didn't put them online because I am currently changing a lot.
      In case you want to eddit this project you are highly welcomed. If you post you eddit please put the link to my page in. (:


      
Images (not up to date!):





![Schematic_Simple-Leds_2025-03-28](https://github.com/user-attachments/assets/465848ae-67b9-4864-8d25-6e831e3d9013)
General schematics (they can sometimes be not 100% up to date)




![image](https://github.com/user-attachments/assets/1e73a608-6ca0-433a-bb53-435418c99cd5)
PCB Layout with text.




![image](https://github.com/user-attachments/assets/78d95939-e9c4-483e-aea5-c668ad30d2a2)
PCB 2D view without the solder on components.



![image](https://github.com/user-attachments/assets/6a541ca6-61ad-4232-8f19-43c2c8af9290)
PCB 3D view with the solder on components.

