<!-- [[> SEO
###### Number: 1.10

###### Title: How to use ReShade and FPS Unlock in Genshin? Guide
###### Description: This document provides a comprehensive installation guide for Genshin Stella Mod, which includes ReShade and FPS unlocking. Follow the step-by-step instructions to enhance your Genshin Impact gaming experience. Learn how to install the mod using the InnoSetup installer, ensuring compatibility with various operating systems. Check your PC's specifications to meet the mod's requirements and enjoy new features seamlessly.
###### Tags: genshin stella mod, genshin impact reshade, fps unlock, installation guide, how-to, supported operating systems, pc requirements, trusted source, avoid harmful downloads, beta version, installation process, innosetup installer, step-by-step guide, download instructions, stella mod launcher, desktop shortcut, game launcher, new features, reshade injection, fps boost, game performance, game modifications, stella mod beta, computer specifications, genshin impact modding, game enhancements, trusted installer, download from official website, computer safety, genshin impact mods
###### Canonical: /genshin-impact-reshade/docs?page=installation
]]> -->

## 🔑 Trusted source {#trusted-source}
To ensure that you have downloaded the necessary files from a trusted source, it is important to verify that you are downloading the installer from the official website [sefinek.net/genshin-impact-reshade](https://sefinek.net/genshin-impact-reshade).
This will help you avoid potentially harmful downloads that may contain viruses or malware. Always be cautious when downloading files from the internet and make sure you trust the source.

## 🌐 Before {#before-the-installation}
Before starting the installation, it is recommended to familiarize yourself with the system requirements of this software. Please note that on some incompatible computers, the software may not function properly.



# ✔️ Fast Installation via InnoSetup {#installation-via-innosetup}
### 1️⃣ Step 1 {#installation-via-innosetup_step-1}
Download the installer from the [homepage](https://sefinek.net/genshin-impact-reshade).

### 2️⃣ Step 2 {#installation-via-innosetup_step-2}
Run the downloaded installer with administrator privileges. The installation path can be chosen freely, but it is recommended to select one that is convenient for you (e.g. `C:\Genshin-Stella-Mod`).
The installation process may take about **30 seconds**

### 3️⃣ Step 3 {#installation-via-innosetup_step-3}
After completing the installation, in some cases, it may be necessary to restart the computer. Once you close the installer window, launch the Stella Mod Launcher shortcut on your desktop if you agreed to create one during the installation process. If not, navigate to the folder where you installed the launcher and run the `Stella Mod Launcher.exe` file.

### 4️⃣ Step 4 {#installation-via-innosetup_step-4}
To inject ReShade and unlock FPS in game, simply click the `Start Game` button in the Stella Mod Launcher.



# ✔️ Manual Installation - Compilation via VSC 2022 {#comililation-via-vsc}
### 1️⃣ Step 1 {#comililation-via-vsc_step-1}
Go to the website https://git-scm.com/download/win and download the appropriate version of Git for your computer. After downloading, proceed with the installation of Git software.
[!IMPORTANT]
Stella Mod does not support `x32-bit` processors!

### 2️⃣ Step 2 {#comililation-via-vsc_step-2}
Launch Windows Terminal or Command Prompt and navigate to the location `C:\`.
```cmd
cd C:\
```

### 3️⃣ Step 3 {#comililation-via-vsc_step-3}
Clone the external repository using the git clone command.
```cmd
git clone https://github.com/sefinek24/Genshin-Impact-ReShade.git
```

### 4️⃣ Step 4 {#comililation-via-vsc_step-4}
Download and install [Visual Studio 2022 Community](https://visualstudio.microsoft.com/vs/community).

### 5️⃣ Step 5 {#comililation-via-vsc_step-5}
Launch the solution:
```cmd
start "Genshin Stella Mod Pack made by Sefinek.sln"
```

### 6️⃣ Step 6 {#comililation-via-vsc_step-6}
Compile each solution (excluding the Win App Packaging Project) starting from the end. You will need to restart the IDE to gain administrator privileges. In the `This task requires the application to have elevated permissions` window, click `Restart under different credentials`.

[!WARNING]
Some solution files are NOT PUBLICLY AVAILABLE due to API server security and similar reasons.


# 🎉 Congratulations!