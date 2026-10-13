---
{"dg-publish":true,"permalink":"/How to switch to Linux/","created":"2026-09-05T13:02:02.094+02:00","updated":"2026-10-08T10:42:05.151+02:00","dg-note-properties":{}}
---

This is not a complete guide. You will need other guides.
This is mostly a list of things I would. In this order.

---
# 1. Prepare
*I would start ~1 year prior to switching your main computer to Linux.*
## 1.1. Switch to FOSS-Software
### Cloud
iCloud or OneDrive is a pain (the corpos behind them dont want do support their software on Linux)
Better: kDrive or MegaSync or Proton Drive (Client for Linux 2026 in Development)
### Password manager
Set up a password manager like Bitwarden or KeePass or check if your PWM is available on Linux already. It really helps when setting up a new computer.
Don't use ecosystem-PWMs like Safari/Apple-Keychain or Chrome/Google-Passwords, use an independent PWM.
### All other software
Check for each and every one of your most important software-apps. Best practise is to switch from a big-tech/proprietary app to a FOSS-version which is supported natively on Linux.
Beside the already mentionned cloud and password-manager, the most frequent/typical things to change are:
- E-Mail-Client/Adressbook (Outlook, Apple Mail, ...)
- Calendar
- Office Suite (Microsoft 365/Office)
- Instant messaging (WhatsApp, Signal, ...)
- Media editing software ((how) do you edit images, audio, video?)
- PDF-Programms (Adobe Acrobat or other specific powerful PDF-App?)
- Work/School/specialist apps (Accounting, Database, CAD, VPN-Client, ...)
Go through your whole software-collection from most used to least used and search for each one:
"x on Linux", "x FOSS alternatives" or "x alternatives on Linux"

There are several options:
- App is already natively supported (e.g. Signal-Messenger)
- you should switch to good FOSS Alternatives (e.g. Thunderbird for E-Mail)
- you have to do technical hacks
### technical software "hacks"
If an "app" can be accessed through the browser, make a Progressive Web App (e.g. web.whatsapp.com)

If you are really dependent on a programm, which is not accessible through the browser and there are no viable Linux-native or FOSS alternatives, you have to set up a VM, Container, Windows-Emulator, Boxes, Wine, Winboat, ...
These "simulate" a Windows-Environment for the programm to run  in.
## 1.2. What if I really need a whole Windows OS for certain Windows-only-Software?
If you need Microsoft-Software like MS Access or others which arent available at all on Linux, you need an option to use Windows from time to time. There are multiple solutions:
### several computers
Decide for example: Home-PC for Linux and the Laptop for Windows.
Then set up the Windows-only Software on the Laptop and the rest on the PC.
### Dual-Boot
If you have a PC, you can put in more than one OS-Drive. So you have C: for the Windows-OS. And then you have a second drive (SSD for example) with the Linux OS on it. You can choose what to boot in the BIOS (during startup). You can even plug in the needed OS-SSD when the PC is shut off.
It is even possible to have two OSses on one drive, but this is technically more advanced.
## 1.3. What about Gaming?!
Check protondb.com. Most games are supported. Steam/Valve has done great work with the compatibility.
Mostly only the **competitive multiplayer games** with strict anticheat are not available on Linux. (e.g.: Apex Legends, Rainbow Six, ...)
**Modding** of games is also more difficult on Linux, as most mods are made for the Windows-Version of the Game.
# 2. Switch to Linux
## 2.1. What computer?
As mentionned earlier: Only switch one computer to Linux in the beginning.
It is good to have a backup for when you have some urgend windows-only task you missed in the first step.

It is most easy if you have a computer you can format (delete everything from) completly. So no left over Drives from Windows and so on. It is possible of course but might give some problems later.
*For example: I wanted to use a drive full of files, which I created on windows. I could access and use it in linux but my cloud-provider couldnt synchronise the files because it hat dome left over permissions from the time it was used in windows. It would have been better if I left the drive and had a seperate one, formatted in linux for linux (different filesystem) and then moved the files in linux from the old to the new drive.*
## 2.2. What Distro?
If its your first Linux-Computer, pick a "beginner" distro.
If you come from Windows just pick Linux Mint. Its like debloated windows with sane defaults and some usefull preinstalled stuff.

Many distros let you try it out before installing it ("Live-Distro"). So you put in the stick with the distro on it and you use the OS while it is only on the stick. Its a wunderful way to klick around and try some features.

If you want to find some other distro or have specific needs: https://distrochooser.de/# or https://distrofighter.com/. I recommend to use a [popular distro](https://distrowatch.com/dwres.php?resource=popularity), so there are many resources if you want to learn or fix bugs. 

Detailed infos about all distros on [Distrowatch](https://distrowatch.com).
## 2.3. Problems?
search online
read documentations
watch tutorials
ask LLMs (AI-Chatbots)

Dont forget to always name the Distro (or partent distro (mostly Debian, Arch, Fedora), so CachyOS --> Arch) in your question.
# 3. After switching
You will need a few hours to a few weeks to acclimatise, depending on your experience with computers and the chosen distro.

Dont give up!

## 3.1. Fun things to do
### visual customisation
try out differen themes, colors, cursors, symbols. Depending on the Desktop Environment (Gnome, KDE Plasma, Cosmic, Cinnamon, ...) you can go very far with customisation. Enjoy!



#guide  #kampagnen/FOSS 