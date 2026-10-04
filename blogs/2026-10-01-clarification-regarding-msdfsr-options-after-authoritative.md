---
title: "Clarification Regarding msDFSR-Options After Authoritative SYSVOL Synchronization"
url: "https://techcommunity.microsoft.com/t5/windows-server-for-it-pro/clarification-regarding-msdfsr-options-after-authoritative/m-p/4561391#M13244"
date: "2026-10-01"
author: "MasPAN74"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=WindowsServer"
---
Hello, I had a SYSVOL synchronization issue between my domain controllers, so I had to perform an authoritative synchronization of DFSR-replicated SYSVOL. The procedure starts by setting msDFSR-Options=1 on the healthy domain controller. However, after completing the procedure and returning the other DFSR-related values on all domain controllers to their default settings, I could not find any clear information about whether msDFSR-Options should also be returned to its default value.
