---
title: "Windows Server 2025 DC — LSASS handle leak identified via WinDbg — authz!AuthzpDeQueueThreadWorker"
url: "https://techcommunity.microsoft.com/t5/windows-server-for-it-pro/windows-server-2025-dc-lsass-handle-leak-identified-via-windbg/m-p/4517940#M13014"
date: "2026-05-09"
author: "RugAmin1"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=WindowsServer"
---
Hello All!! Im having a problem, LSASS crashes on a Windows Server 2025 Domain Controller, I identified what appears to be the root cause using WinDbg memory dump analysis. Sharing this hoping someone else has seen it or Microsoft can confirm.
