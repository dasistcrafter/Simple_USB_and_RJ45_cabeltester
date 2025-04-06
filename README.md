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





![image](https://github.com/user-attachments/assets/2c8a4802-1f6b-4848-83dc-dc6040bb9a71)

General schematics (they can sometimes be not 100% up to date)




![image](https://github.com/user-attachments/assets/3acec1f5-eefe-4396-a6e4-18b9c7869637)

PCB Layout with text.




![image](https://github.com/user-attachments/assets/2538f760-f7e3-4e2c-855d-64c7b3ad78f5)

PCB 2D view without the solder on components.



![image](https://github.com/user-attachments/assets/2b442c65-e362-4564-a8e7-849542e4a0e6)

PCB 3D view with the solder on components.

