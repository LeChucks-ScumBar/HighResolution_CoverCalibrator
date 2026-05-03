This project ist forked from https://github.com/10thTeeAstronomy/DarkLight_CoverCalibrator

I have developed a high-resolution flat panel. It has 4,095 brightness levels instead of just 255. In addition, the controller uses an adjustable current source without PWM, enabling constant brightness without flickering.

Current status as of May 2, 2026: 
- Software runs on Arduino and Nina
- Circuit diagram created and simulated

Pending
- Upload circuit diagram/PCB to Git
- Order/build electronics
- 3D printing
- Test assembly
- - - - - - - - - - - - - - - Original text - - - - - - - - - - - - - - - - - - 
# DarkLight Cover/Calibrator (DLC)
https://www.youtube.com/watch?v=G-Wl4XsGtBc

The **DarkLight Cover/Calibrator (DLC)** is a DIY project to build a motorized telescope cover, flat panel, or a combined flip-flat system. Designed for versatility and modularity, the DLC supports a variety of setups:

- **Light Panel Only** – Wall-mounted calibration panel (no servo)  
- **Servo(s) Cover Only** – Flip cover for sky flats and darks  
- **Flip-Flat Combo** – Integrated servo and light panel system

The DLC is compatible with both **ASCOM** and **INDI** platforms, enabling seamless automation through:

- The **DLC Windows app** (ASCOM only)
- ASCOM automation software (via the **ICoverCalibrator** driver)
- The **INDI** platform for Linux/macOS users

Optional **dew heating** reduces the need for additional equipment and cabling.

> ⚠️ While the DLC **does NOT** make the telescope weatherproof or dustproof, it provides hands-off control and dark/light calibration for astrophotography in the field or an observatory.

---

## 📦 Features

- Build as a **standalone cover**, **light panel**, or **combination flip-flat** mechanism
- **Optional physical buttons** for manual servo and light control
- **Multi-servo capable** with dual independent angle support
- 7 **servo easing options** (ease-in/out and linear)
- **Adjustable servo speed**
- **Optional dual-channel dew heater** with built-in safety
- **ASCOM** and **INDI** driver support
- Up to **270-degree movement** range
- **Reverse voltage protection** on 12VDC input
- Save **brightness and position** to EEPROM
- **Electronically adjustable brightness control**
- **Smooth illumination circuit** (eliminates PWM banding)
- Save **broadband and narrowband calibration values**

---

> 📢 **Personal and academic use only.**  
> Commercial use is **prohibited** without written permission.  
> See full license and legal terms below.

---

## ⚠️ Security Notice

Only download DLC software from the official GitHub repository:  
[https://github.com/iwannabswiss/DarkLight_CoverCalibrator](https://github.com/iwannabswiss/DarkLight_CoverCalibrator)

Do **not** trust `.exe`, `.msi`, `.zip`, or `.tar.gz` files from unofficial sources, which may contain malware or unsupported changes.

---

## 📜 License

© 2020–2025 10th Tee Astronomy. All rights reserved.

This project is licensed under the  
[Creative Commons Attribution-NonCommercial 4.0 International License](https://creativecommons.org/licenses/by-nc/4.0/)

- You may **share and adapt** the materials for **personal or academic use**
- **Commercial use is prohibited** without written permission
- Modified versions must credit the original work
- See `LICENSE.md` for full terms

---

## 💼 Commercial Use

If you are interested in using this project for commercial purposes,  
please contact the author for licensing options:

📧 **Contact**: 10thTeeAstronomy@gmail.com

---

## 🧾 Legal Notice

This project is protected by international copyright law and treaties.  
All content is provided **"as is"** with no warranty or guarantee of suitability.

---

Happy imaging! 🌌
