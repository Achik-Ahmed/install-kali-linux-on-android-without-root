# How to Install Kali Linux on Android (Without Root) – 100% Working and Safe

![How to Install Kali Linux in Android](https://github.com/Achik-Ahmed/install-kali-linux-on-android-without-root/blob/main/how-to-install-kali-linux-in-android.jpg)

Hey friends! Do you want to install **Kali Linux** on your **Android phone** without rooting it? If yes, then you're in the right place. In this GitHub repo, I’m sharing the easiest and 100% working method that I have already explained step-by-step in my blog.

**Read Full Blog Post:**  
https://www.achik.us/how-to-install-kali-linux-on-android-without-root/

This method is beginner-friendly and doesn’t harm your phone. Even if you’ve never used Linux before, don’t worry — just follow the steps one by one.

---

## What is Kali Linux?

Kali Linux is a special version of Linux made for people who want to learn **ethical hacking**, **cybersecurity**, and **Linux commands**.  
It comes with many powerful tools like **Nmap**, **Wireshark**, **Metasploit**, and more.  

Usually, it runs on computers, but with this method, you can run it directly on your Android phone without root.

---

## What You’ll Need

Before you start, make sure you have:

- An Android phone (any brand is okay)
- **Termux app** (download from F-Droid, not Play Store)
- Good internet (Wi-Fi is better)
- Around 2–3 GB free space
- 1 GB internet data (approx)

---

## Step-by-Step Installation Guide

Here are the steps to install kali Linux on Android without root:

### Step 1: Install Termux  
Go to F-Droid and install Termux.  
Don’t use the Play Store version — it’s old and might not work.

### Step 2: Update and Install Packages  
Open Termux and paste these:
```
pkg update -y
pkg install wget curl proot tar -y
```
This will prepare everything you need to install Kali.

### Step 3: Download Kali Linux Script  
Paste this command:
```
Given in the full blog article.sh
```
https://www.achik.us/how-to-install-kali-linux-on-android-without-root/

It will download the installer file.

### Step 4: Give Permission to Run Script  
Run this command:
```
chmod +x kali-xfce.sh
```

### Step 5: Run the Script to Install Kali Linux  
Now type this and relax:
```
bash kali-xfce.sh
```
This will take around 10–30 minutes, depending on your phone and internet speed.  
📌 Don’t close Termux while it’s running.

---

## Done! Kali Linux is Installed

After the installation process is successfully completed, you will see a message like:
```
Welcome to Kali Linux! root@localhost:~#
```
This means it kali linux is successfully installed on your Android phone.
You can now use **Kali Linux tools and commands** on your phone.

---

## How to Start Kali Linux Again (Next Time)

Whenever you want to open Kali Linux again:

1. Open Termux  
2. Type:
```
./start-kali.sh
```

That’s it! You will be back inside Kali.

---

## Want to Use GUI? (Kali with Screen Mode)

If you want to use Kali Linux in a graphical user interface version then you can follow these steps:

1. Inside Kali, type:
```
apt update
apt install xfce4 xfce4-goodies tightvncserver -y
```

2. Create folder:
```
mkdir -p /root/.config/tigervnc
```

3. Start VNC:
```
vncserver :1
```

4. Set any password (nothing will show while typing)

5. Install **VNC Viewer** from Play Store and connect to:
```
localhost:5901
```

Now enjoy Kali Linux with a full-screen GUI interface! Looks like a real computer.

---

## How to Delete Kali Linux (If You Want)

If you ever want to remove everything, just type this in Termux:
```
rm -rf kali-fs kali-xfce.sh start-kali.sh
```

This will delete every file related to Kali Linux from your phone.

---

## 💡 Some Extra Tips

- Make sure your phone doesn’t go to sleep while installing.
- Don’t turn off internet during installation.
- If anything fails, just run the script again.
- To install extra tools:
```
apt-get install <tool-name>
```
Example:
```
apt-get install nmap
```

---

## 📎 Full Blog Guide

Want all commands, images, and tips in one place?  
Read here: [https://www.achik.us/how-to-install-kali-linux-on-android-without-root/](https://www.achik.us/how-to-install-kali-linux-on-android-without-root/)

This article is written in **simple language** and **easy words** so that you can easily understand.

---

⭐ If you liked this project, please **star this repo** and try it yourself.  
It’s a fun way to explore Kali Linux and Linux tools — all from your phone!
