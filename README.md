# JioPc-Vps 🚀

## 📩 Contact

If you’re interested in using or buying this package, feel free to connect:

WhatsApp: **+919771241425**

This project provides a setup to turn **Jio PC (Ubuntu Jammy)** into a **VPS-like environment** with support for:

- ✅ RDP (Remote Desktop Protocol) for remote access  
- ✅ Unofficial installation of **Android Studio**  
- ✅ VPS-style usage on low-cost Jio PC hardware  

---

## Features
- Jio PC configured as a lightweight VPS  
- Remote access via RDP (connect from Windows, Mac, Linux)  
- Optional Android Studio setup for development (unofficial build)  
- Minimal resources optimized for Jio hardware  

---

## Requirements
- Jio PC with Ubuntu Jammy (22.04)  
- Internet connection  
- Basic Linux knowledge (terminal/TTY)  

---

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/JioPc-Vps.git
   cd JioPc-Vps


## Setup RDP

```sudo apt update
sudo apt install xrdp -y
sudo systemctl enable xrdp
sudo systemctl start xrdp


## (Optional) Install Android Studio (Unofficial)

## Download Android Studio from official site.

Extract and run the installer:

tar -xvzf android-studio-*.tar.gz
cd android-studio/bin
./studio.sh

## Usage

Connect via Remote Desktop (RDP) using your Jio PC’s IP address.

Run Android Studio from desktop environment (if installed).

Use Jio PC as a budget-friendly VPS for light workloads and testing.

##  Disclaimer ⚠️

This is an unofficial setup. Android Studio and RDP integration are not officially supported by Jio. Use at your own risk.
