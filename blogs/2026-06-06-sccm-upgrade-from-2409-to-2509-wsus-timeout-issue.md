---
title: "SCCM- Upgrade from 2409 to 2509 WSUS timeout issue"
url: "https://techcommunity.microsoft.com/t5/windows-server-for-it-pro/sccm-upgrade-from-2409-to-2509-wsus-timeout-issue/m-p/4526101#M13032"
date: "2026-06-06"
author: "cidk2000"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=WindowsServer"
---
Had a working task sequence on 2409 that performed software updates at the end of the task sequence. Upgraded to 2509 - I get a timeout issue when getting to that point on the task sequence. Ive performed maintenance on the WSUS Server, (obsolete, expired etc) I removed the Software Update Point - and re installed it selected the Products of Server 2016,2019, server operating system 21h2 , Windows 10 1903 or later and Windows 11.
