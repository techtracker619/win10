# 💻 Lab: Install Windows 10 Client on VirtualBox

This lab walks through the process of downloading, installing, and configuring a Windows 10 Client VM in Oracle VirtualBox. This setup is ideal for Active Directory labs or client-side testing.

---

## 🧩 Step-by-Step Guide

### 1. 🧲 Download Windows 10 ISO
- Visit the official Microsoft site to download Windows 10 ISO:
  👉 https://www.microsoft.com/software-download/windows10ISO
- Select your edition and language.
- Choose **64-bit Download** and save it to your computer.

---

### 2. 🧰 Launch VirtualBox & Create a New VM
- Open **Oracle VM VirtualBox**.
- Click **New** ➜ Name it `Win10Client`.
- Type: **Microsoft Windows** | Version: **Windows 10 (64-bit)**
- Allocate RAM: **4096 MB** (recommended).
- Create a virtual hard disk: **50 GB** VDI, dynamically allocated.


---

### 3. 💿 Mount Windows 10 ISO
- Go to **Settings > Storage**.
- Under **Controller: IDE**, click the empty disk icon.
- Choose a disk file ➜ select the downloaded Windows 10 ISO.


---

### 4. 🚀 Start the VM
- Press **Start** to boot into the ISO.
- Select Language, Time Format, Keyboard (keep defaults) ➜ Click **Next**.

📸 *Screenshot Example*  
![imagealt](https://github.com/techtracker619/win10/blob/ea197cdb5e25ea822b7b01f795ba175d29e5a615/screenshots/VirtualBox_Win10_30_06_2025_00_14_11.png)

---

### 5. 🔑 Skip Product Key
- Click **I don’t have a product key** to continue without activation.

![imagealt](https://github.com/techtracker619/win10/blob/ea197cdb5e25ea822b7b01f795ba175d29e5a615/screenshots/VirtualBox_Win10_30_06_2025_00_16_35.png)

---

### 6. 🧩 Choose Windows 10 Edition
- Choose **Windows 10 Home** or **Pro** ➜ Click **Next**.

![imagealt](https://github.com/techtracker619/win10/blob/ea197cdb5e25ea822b7b01f795ba175d29e5a615/screenshots/VirtualBox_Win10_30_06_2025_00_16_46.png)

---

### 7. 📜 Accept License & Custom Install
- Accept terms ➜ Choose **Custom: Install Windows only (advanced)**.
- Select your virtual hard drive ➜ Click **Next**.


---

### 8. ⏳ Wait for Installation to Complete
- Windows will install the OS (this may take 10–15 minutes).
- The VM will reboot automatically.

---

### 9. 👤 Configure Windows Setup
- Create a local user or sign in with Microsoft.
- Select your privacy preferences ➜ Finalize setup.

---

### 10. 🌐 Enable Network for Domain or Internet Access
- Open **Control Panel** ➜ Click **Network and Sharing Center**.

![imagealt](https://github.com/techtracker619/win10/blob/ea197cdb5e25ea822b7b01f795ba175d29e5a615/screenshots/VirtualBox_Win10_30_06_2025_01_32_25.png)
![imagealt](https://github.com/techtracker619/win10/blob/ea197cdb5e25ea822b7b01f795ba175d29e5a615/screenshots/VirtualBox_Win10_30_06_2025_01_33_24.png)

- Click **Change adapter settings** on the left.
- Right-click **Ethernet > Properties**.

![imagealt](https://github.com/techtracker619/win10/blob/ea197cdb5e25ea822b7b01f795ba175d29e5a615/screenshots/VirtualBox_Win10_30_06_2025_01_34_49.png)

---

## 🧠 Key Skills Practiced
- VirtualBox VM setup
- Windows 10 ISO handling
- OS installation process
- Network configuration
- Lab-ready client VM setup

---

## 🤝 Author  
**Anthony Jenkins**  
*Follow for more hands-on IT and cybersecurity labs!*

<!-- 📚 Byte Library Section -->
<h3>📚 Byte Library</h3>
<p>
  Explore free IT & Cybersecurity resources, labs, and articles built for beginners and career switchers.
  <br />
  👉 <a href="https://byte-library.com/" target="_blank" style="text-decoration: none; font-weight: bold;">
    Visit Byte Library
  </a>
</p>

