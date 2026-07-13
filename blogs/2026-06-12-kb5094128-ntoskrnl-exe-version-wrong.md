---
title: "KB5094128 ntoskrnl.exe version wrong?"
url: "https://techcommunity.microsoft.com/t5/windows-server-for-it-pro/kb5094128-ntoskrnl-exe-version-wrong/m-p/4527790#M13035"
date: "2026-06-12"
author: "BasP"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=WindowsServer"
---
For update KB5094128 The list of updated files contains an ntoskrnl.exe with file version 10.0.20348.5257 which in my opinion should be 10.0.20348.5256. https://go.microsoft.com/fwlink/?LinkId=2368532 We use scanning tools which rely on this list of updated files. But the installed file version is different and therefore our scanning tools report these installations as "vulnerable" After applying patch KB5094128 the version of \windows\system32\ntoskrnl.exe is 10.0.20348.5256 Does anybody know if the information in this .csv is wrong?
