---
title: "ADFS migration issue from 2016 OS to 2025 OS."
url: "https://techcommunity.microsoft.com/t5/windows-server-for-it-pro/adfs-migration-issue-from-2016-os-to-2025-os/m-p/4562512#M13255"
date: "2026-10-07"
author: "naveen0007"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=WindowsServer"
---
We have an ADFS 2016 farm (10.0.14393.6078, Farm Behavior Level 3) using a gMSA service account. We are trying to add an ADFS 2025 node (10.0.26100.33158) using Add-AdfsFarmNode. HTTP SPNs are correctly registered and visible in Active Directory, yet Add-AdfsFarmNode fails with "There were no SPNs set on the service account".
