---
title: "Secure Boot update still pending on deadline day"
url: "https://techcommunity.microsoft.com/t5/windows-server-for-it-pro/secure-boot-update-still-pending-on-deadline-day/m-p/4530646#M13044"
date: "2026-06-24"
author: "LouisT"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=WindowsServer"
---
After checking the registry keys on 2x VMs which run services for a number of important customers I found they both have: UEFICA2023Error 2147942750 Apparently this means they're pending a reboot. https://blog.mindcore.dk/2026/04/secure-boot-certificate-update-intune/ I can't reboot the VM inside working hours, can they be rebooted after the deadline or do I need to disable Secure Boot on the VMs? I'm concerned I'll have to disable Secure Boot before they're next rebooted for Windows updates.
