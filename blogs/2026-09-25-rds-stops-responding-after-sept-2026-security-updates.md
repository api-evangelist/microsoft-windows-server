---
title: "RDS stops responding after Sept. 2026 security updates"
url: "https://techcommunity.microsoft.com/t5/windows-server-for-it-pro/rds-stops-responding-after-sept-2026-security-updates/m-p/4559796#M13227"
date: "2026-09-25"
author: "DoJU70"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=WindowsServer"
---
Hi All, I have one last Windows Server 2012 R2 ESU VM in PROD, used for a legacy SQL Server / Video / Audio solution. Since installing KB5123066: RDP cannot connect to the VM The Windows Desktop is unstable File Explorer is unresponsive Windows Update services will not start As per: https://learn.microsoft.com/en-us/windows/release-health/resolved-issues-windows-8.1-and-windows-server-2012-r2#4981msgdesc Since Windows Update services won't start, we can't deploy the fix (KB5129243) through normal means. Attempts so far: KIR (Known Issue Rollback) via GPO — deployed the Windows 8.1 and Windows 
