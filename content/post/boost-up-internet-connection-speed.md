+++
date = 2016-04-20
lastmod = 2017-09-03
draft = false
tags = ["boost", "connection speed"]
title = "boost up internet connection speed"
math = true
summary = """
If you follow some tips as my guide, then you will be able to get more than internet connection speed. This method is applicable for Windows 7, 8 or 1o operating system without any external software. Ok lets start to boost up internet connection speed. 
"""

[header]
image = "boost-internet-speed.jpg"
caption = "boost up internet connection speed"

+++

In this tutorial i gonna show how to boost internet connection speed up on windows computer. By default Microsoft corp configured some parameter that exactly decreased your internet connection more than 12 to 15 %. But if you follow some tips as my guide, then you will be able to get more than internet connection speed. This method is applicable for Windows 7, 8 or 1o operating system without any external software. Ok lets start to boost up internet connection speed.

**Step 1. Drain out DNS Cache**

Open a Command terminal by Run as administrator. Now type IPCONFIG /FLUSHDNS and press enter to Flush DNS. It look like's bellow picture.

**Step 2. Disable Unnecessary services**

Some of Windows services can be decrease your internet speed, so you have to control more than 7 services. Open Run Command prompt [ Windows + R] Type Services.msc and press enter A services window will be open. Now you have to changed Automatic to Manual startup type of 7 services [i.e : Diagnostic Policy Service, Distributed Link Tracking Client, Offline Files, Performance Logs & Alerts, Program Compatibility Assistant Service, Secondary Logon, Windows Error Reporting Service, Windows Image Acquisition (WIA) ] See the image bellow.

**Step 3. Reset Winsock**

When you restart winsock, then your internet connection will be increased. You can follow this step again after few day to boost internet connection speed. Open Command Prompt "CMD" by Run as administrator. Now type NETSH INT IP RESET C:\RESETLOG.txt See the image bellow

**Step 4. Update Network Card Driver**

By default windows 10 has automatic update feature, so if you are windows 7 or 8 user now you have to update network card driver [i.e : WLAN driver, Ethernet Driver etc] Follow image bellow

**Step 5. Disable Bandwidth Reserves**

Windows reserved some bandwidth by default, so you have to disable it. Open run command prompt [Windows + R] Now type gpedit.msc and press enter Local group policy window will be open. Then go to step by step as "Local Computer Policy\Computer Configuration\Administrative Templates\Network\QoS Packet Scheduler" Now right click on "Limit reservable bandwidth" and edit. Enable this option and set limit to "0" Click Apply and OK, see the image bellow. Close Local Group policy window.
Last step: Open Run command prompt type "regedit" without quote.
Registry Editor window will be open. Now go to "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows" Now click Pshed click folder then you'll be see "NonBestEffortLimit" function on right side. Right Click it to modify value. Now set it 1 to 100 with decimal tab, see the image bellow. :D You are almost done. Restart your pc and enjoy 100% internet speed on your computer.
