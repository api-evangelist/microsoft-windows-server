---
title: "HA Print Service Windows 2025 Server"
url: "https://techcommunity.microsoft.com/t5/windows-server-for-it-pro/ha-print-service-windows-2025-server/m-p/4558112#M13208"
date: "2026-09-19"
author: "ValdirRodrigues"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=WindowsServer"
---
There are two servers running Windows Server, both with the Print Spooler service enabled. They share the same printer queues. I created a CNAME alias named "printcore" pointing to Server01; the client can successfully connect to the printer using the UNC path `\\printcore\hpprincipal`, but if I change the alias to point to Server02, the client's connection to the printer fails.
