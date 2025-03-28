# Simple_USB_and_RJ45_cabeltester
A simple cabel tester for USB-A;USB-C;Micro-UBS;USB-B;RJ45


DISCLAIMER: This is a work in progress project. Please do not be suprised to find errors, and if please leave me some feedback so I can fix it ASAP.
I will be ordering the first batch in the coming days for testing. If you choose to build this PCB yourself, you do so at your own risk. I am not liable for any damage to property or injury that may result from using this design.




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


It works by applying 5 volt on site A.
The power is the transmitted over the cabel.
If the string inside the cabel is broken the led should not light up.
There can be false OK results becase 2 Conductors are touching inside the wire. if this is the case the current desing can not detect this.(I am planig a version with a miocrocontorler in the future that can detect these kinds of malfunctions)




the text above can also be found printet on the PCB.

![image](https://github.com/user-attachments/assets/78d95939-e9c4-483e-aea5-c668ad30d2a2)
