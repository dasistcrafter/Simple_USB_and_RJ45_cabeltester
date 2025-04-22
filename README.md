---

# Simple USB and RJ45 Cable Tester

A simple cable tester for USB-A, USB-C, Micro-USB, USB-B, and RJ45.

---

### ⚠️ Disclaimer

This is a **work-in-progress** project. Please don’t be surprised if you find errors – and if you do, please leave feedback so I can fix them ASAP.

I will be ordering the first batch for testing in the coming days.  
If you choose to build this PCB yourself, you do so **at your own risk**.

**I am not liable for any damage to property or injury that may result from using this design.**

---

## 🔧 Description

This is a small cable tester.  
It’s designed to test whether a connection through a conductor is present or not.

You can use it to identify **broken** or **cheap cables**.

---

## 📖 Cable Tester v1.0 – Instructions

```
1. Plug the cable into Side A and Side B.
2. Connect power using the POWER Micro-USB port.
3. Set DIP switches to ON for the lines you want to test.
4. Press the TEST button.
5. If an LED turns on, that line works correctly.
```

➡️ **DO NOT PLUG INTO ANY DEVICE!**  
It can kill it **instantly!**

(The text above is also printed on the PCB.)

---

## ⚙️ How it works

The tester applies **0–2.6V** on Side A.  
Power is then transmitted over the cable.

If a conductor inside the cable is broken, the LED should **not** light up.

You can select individual lines using the DIP switches.

If you don’t want to keep pressing the button, you can **bridge the jumper** next to the switch.  
⚠️ *Note: This may cause more stress on the cable and is **not recommended***.

The voltage can be adjusted using the **potentiometer**.

---

## 📁 Project Files

You can request the files from me.  
I haven’t uploaded them yet, as I’m still making many changes.

If you edit this project, you’re **highly welcome** to share it –  
please just include a link back to my page. 

---

## 📸 Images

### Circuit Board  
![image](https://github.com/user-attachments/assets/98cfade1-ffd6-45b8-b725-18b8748cd2e3)


### 2D View (without soldered components)  
![2D View](https://github.com/user-attachments/assets/ea809f87-288a-4dc7-8c59-40f942e1b4d2)

### 3D View (with soldered components)  
![3D View](https://github.com/user-attachments/assets/91d4536b-3efe-4cd2-b32e-1f3f07d95f3f)

---

## 🔗 More Info

👉 [github.com/dasistcrafter](https://github.com/dasistcrafter)

---
