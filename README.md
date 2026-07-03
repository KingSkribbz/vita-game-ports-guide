# susbaconhairman skribbler's Vita Game Ports Guide
!!! note Contact me
	skribbler#1095 on Discord, and susbaconhairman@gmail.com
---
###Prerequisites
!!! danger
	If your PS Vita doesn't already have custom firmware (CFW), go to https://vita.hacks.guide to add it.
!!! danger Plugins
	Some games require plugins to be playable, which you can get from this app: https://github.com/ONElua/AutoPlugin2. Download the latest release on the page, and install the VPK to your console. Plugins that need to be installed will be listed on each game. Some plugins may also be on VitaDB, such as [ShaRKBR33D](https://vitadb.rinnegatamante.it/#/info/997) (```libshacccg.suprx```), and [NoTrpDrm](https://vitadb.rinnegatamante.it/#/info/1120) (```NoTrpDrm.suprx```).
!!! warning
	Windows as your computer's OS is recommended, although you should be able to use any device for copying files to the card, as long as it's able to download things and has a (micro)SD card reader or has a USB port, for USB data transfer. You should also have some form 7-zip installed for some of the files in this guide. For Windows, Mac, and Linux, you can get it at https://7-zip.org.
- If you want to request a game to be added to this list, the game must not be "easy" to install (like a pre-compiled VPK), it has to have game files that need installation too.
- In the downloads section, for each of the game's files, all "official" file downloads - that are made by the original provider of the files, listed after the installation instructions of each game - will be below the file's bold name. "Unofficial" mirrors - made by me - will be below the "official" file downloads. All file downloads will have a link description that is the site they are hosted on, like GitHub or Medafire. Mirrors made by me will have the site it's hosted on and the word "mirror" in it.
- All the files hosted by me on MEGA can be found here: https://mega.nz/folder/XVp3larJ#xZLCtdw9lNsEbaTbdBmBIA
- All file sizes listed on this page are in -bytes (XB), not in -bibytes (XiB).
- Be sure to check out my guide for the 3DS at [https://rentry.org/3ds-game-ports-guide](https://rentry.org/3ds-game-ports-guide)!
---
!!! info Table of Contents
	[TOC2]
---
###Crazy Taxi
![Crazy Taxi](https://u.cubeupload.com/susbaconhairman/crazytaxi.png)
!!! note Required plugins
	```libshacccg.suprx```, ```kubridge.skprx```, and ```fd_fix.skprx```. Do not install ```fd_fix.skprx``` if you are using repatch plugin.
> **Game files**
(114.31 MB) **crazytaxi.rar**
[**MEGA**](https://mega.nz/file/5jg1CTqK#J1vgZNEKO1dolWk-CoHz9_hIF1u0AtvtQ63VlBSdJDQ)

[MEGA mirror](https://mega.nz/file/fV4EibhJ#Ns9jUpIeg-4YEH3ZqtA3OYb0ZMIMJc6x1pBbdYcu5xU) | [Fileditch mirror](https://small.fileditchstuff.me/s5/ueiMqRQXsdaVqkbshBfo.rar)

> **Launcher**
(1.40 MB) **CRAZYTAXI.vpk**
[**GitHub**](https://github.com/TheOfficialFloW/crazytaxi_vita/releases/download/v1.2/CRAZYTAXI.vpk)

[MEGA mirror](https://mega.nz/file/GZ4QxIAT#KL-vFPNLjGeqy9iXy1wm0tZsJjBfVmXkCcBAT2lTMMs) | [Fileditch mirror](https://small.fileditchstuff.me/s5/zhrNEVCpnWPvspVhePGK.vpk)
!!! info Installation
	Extract ```crazytaxi.rar```, then take the ```main.obb``` and ```libgl2jni.so``` files and put them in ```ux0:data/crazytaxi/```. Finally, download the VPK launcher, put it on your memory card, and install it with VitaShell.
!!! note
	Links taken from https://github.com/TheOfficialFloW/crazytaxi_vita and https://discord.gg/bgP7AYjSyn.
---
###Grand Theft Auto: San Andreas
![GTA San Andreas](https://u.cubeupload.com/susbaconhairman/gtasa.png)
!!! note Required plugins
	```libshacccg.suprx```, ```kubridge.skprx```, and ```fd_fix.skprx```.
> **Game files**
(1.44 GB) **gtasa-20230121T140417Z-001.zip**
[**MediaFire**](https://www.mediafire.com/file/uhl1bmgpiiz9slw/gtasa-20230121T140417Z-001.zip/file)

[MEGA mirror](https://mega.nz/file/6RgwCIJD#ORoq8tO7QBX_3tyq4EBwvv6e3HuWJG0OC0cdacPk11g) | [Fileditch mirror](https://big.fileditchstuff.me/b23/ZiPhyZRJlNCoXWOasnIk.zip)

> **Launcher**
(1.39 MB) **GTASA.vpk**
[**GitHub**](https://github.com/TheOfficialFloW/gtasa_vita/releases/download/v2.1/GTASA.vpk)

[MEGA mirror](https://mega.nz/file/uEAzUaiR#QH1Y-Rve290oAuQxwGSfJshSZo0dGWQv1VIOtGrThic) | [Fileditch mirror](https://small.fileditchstuff.me/s6/LCZSXnTFcnOIjuAbXTts.vpk)
!!! info Installation
	Extract the ```/gtasa/``` folder from ```gtasa-20230121T140417Z-001.zip``` to ```ux0:data/```. Finally, download the VPK launcher, put it on your memory card, and install it with VitaShell.
!!! note
	Files taken from https://github.com/TheOfficialFloW/gtasa_vita and https://discord.gg/bgP7AYjSyn.
---
###Grand Theft Auto 3
![GTA 3](https://u.cubeupload.com/susbaconhairman/gta3.png)
!!! note Required plugins
	```fd_fix.skprx```. Do not install ```fd_fix.skprx``` if you are using repatch plugin.
> **Game files and VPK**
(1.51 GB) **GTA3_v1.4.rar**
[**MediaFire**](https://www.mediafire.com/file/qkimmc9szrswm35/GTA3_v1.4.rar/file)

[MEGA mirror](https://mega.nz/file/CYB00Q6K#DI0AtR4u-0wG-Mb3chib5-DW4PMerfEdtBLtNsU9fFA) | [Fileditch mirror](https://big.fileditchstuff.me/b23/rKxrUOsVMlyslQQkYxss.rar)
!!! info Installation
	Extract the ```/data/gta3/``` folder from ```GTA3_v1.4.rar``` to ```ux0:data/```. Then, take the ```GTA3_re3_v1.4.vpk``` in the archive, put it on your memory card, and install it with VitaShell.
!!! note
	Files taken from https://discord.gg/bgP7AYjSyn.
---
###Bully: Anniversary Edition
![Bully](https://u.cubeupload.com/susbaconhairman/bully.png)
!!! note Required plugins
	```kubridge.skprx``` and ```fd_fix.skprx```. Do not install ```fd_fix.skprx``` if you are using repatch plugin.
> **Game files**
(2.76 GB) **Bully.zip**
[**MEGA**](https://mega.nz/file/rZAHgISR#9s76gyV9li2jNSdMJALwFEYFqGu9PeA3TVqdqS1DE2A) | [**Fileditch**](https://big.fileditchstuff.me/b23/TtuCNfsBSluUCEqCeaL.zip)

> **Launcher**
(875 KB) **Bully.vpk**
[**GitHub**](https://github.com/TheOfficialFloW/bully_vita/releases/download/v1.0/Bully.vpk)

[MEGA mirror](https://mega.nz/file/iRRzgKab#iXOMJ71-vz4cagEL-tVQ4EFSFpSeWwJbq52-7cqcOMc) | [Fileditch mirror](https://small.fileditchstuff.me/s6/psuztDaYMPbZYnHxSjNq.vpk)
!!! info Installation
	Extract the ```/Bully/``` folder from ```Bully.zip``` to ```ux0:data/```. Then, copy ```Bully.vpk``` to your memory card, and install it with VitaShell.
!!! note
	Files taken from https://discord.gg/bgP7AYjSyn and https://github.com/TheOfficialFloW/bully_vita.
---
###Modern Combat 3
![Modern Combat 3](https://u.cubeupload.com/susbaconhairman/mc3.png)
!!! note Required plugins
	```kubridge.skprx```, ```NoTrpDrm.suprx```, ```libshacccg.suprx``` and ```fd_fix.skprx```. Do not install ```fd_fix.skprx``` if you are using repatch plugin.
> **Game files**
(1.41 GB) **mc3.zip**
[**MEGA**](https://mega.nz/file/vUgkTQJa#3B61JMo_JJC0sZu9cnsLfc9EUJs2_Kga71Fn_RbHXAM) | [**Fileditch**](https://big.fileditchstuff.me/b23/elVWNSgEXGenGZPomTW.zip)

> **Launcher**
(3.68 MB) **ModernCombat3-v1.0.vpk**
[**GitHub**](https://github.com/v-atamanenko/mc3-vita/releases/download/v1.0/ModernCombat3-v1.0.vpk)

[MEGA mirror](https://mega.nz/file/SAZURDzS#kaKXoiLmhAeca1FE_sUVFZHoNGl7Nal6-MkCJtKWnw8) | [Fileditch mirror](https://small.fileditchstuff.me/s6/fXbODRnDhWjdLaiMxePK.vpk)
!!! info Installation
	Extract the ```/mc3/``` folder from ```mc3.zip``` to ```ux0:data/```. Then, copy ```ModernCombat3-v1.0.vpk``` to your memory card, and install it with VitaShell.
!!! note
	Files taken from https://github.com/v-atamanenko/mc3-vita and https://apkaward.com/modern-combat-3-fallen-nation, compiled by me.
---
###Grand Theft Auto: Chinatown Wars
![GTA Chinatown Wars](https://u.cubeupload.com/susbaconhairman/gtactw.png)
!!! note Required plugins
	```kubridge.skprx```, ```libshacccg.suprx```, and ```fd_fix.skprx```. Do not install ```fd_fix.skprx``` if you are using repatch plugin.
> **Game files**
(489.72 MB) **GTACTW_v1.2.rar**
[**MediaFire**](https://www.mediafire.com/file/9zrbq9ciga9879e/GTACTW_v1.2.rar/file)

[MEGA mirror](https://mega.nz/file/OIAGnbBK#hnq_2mZIqbUWiYv1aEh2n18l7NHYreYpfsg9jAc67eU) | [Fileditch mirror](https://big.fileditchstuff.me/b23/gMwzqtGLlZoUhsmoolrf.rar)

> **Launcher**
(955 KB) **GTACTW.vpk**
[**GitHub**](https://github.com/TheOfficialFloW/gtactw_vita/releases/download/v1.2/GTACTW.vpk)

[MEGA mirror](https://mega.nz/file/eRh3iJwD#M68s0ApJbsuTzdvpwvC_O4FGY-xKuGu4-NXlP4NG6yU) | [Fileditch mirror](https://small.fileditchstuff.me/s6/JNorZxkiaPmbdQaOfiU.vpk)
!!! info Installation
	Extract the ```/data/gtactw/``` folder from ```GTACTW_v1.2.rar``` to ```ux0:data/```. Then, copy ```GTACTW.vpk``` to your memory card, and install it with VitaShell.
!!! note
	Files taken from https://discord.gg/bgP7AYjSyn and https://github.com/TheOfficialFloW/gtactw_vita.
---
###The Simpsons: Hit and Run
![The Simpsons: Hit and Run](https://u.cubeupload.com/susbaconhairman/hitandrun.png)
!!! note Required pugins
	```libshacccg.suprx```.
> **Game files**
(xx MB) **hitandrun.zip**
[**MEGA**](https://mega.nz/file/SVhAHJTL#7z99kDMitVszceDHe-afbOzejbz5uAYe5ppRdNJ2RiE)

> **Launcher**
[**GitHub**](https://github.com/ZenoArrows/The-Simpsons-Hit-and-Run/releases/download/v0.6.1/SimpsonsNTSC.vpk)

[MEGA mirror](https://mega.nz/file/TZYX1CCA#-1bmrAvuZxIOdd4VMNFq-rwFQAq27bBH8KTMKaYN8Bs)
!!! info Installation
	Extract the ```/simpsons/``` folder from ```hitandrun.zip``` to ```ux0:data/```. Then, copy ```SimpsonsNTSC.vpk``` to your memory card, and install it with VitaShell.
!!! note
	Files from https://github.com/ZenoArrows/The-Simpsons-Hit-and-Run and https://www.myabandonware.com/game/the-simpsons-hit-run-bg6
---
###Stuff that will probably come soon
Hollow Knight
Geometry Dash
