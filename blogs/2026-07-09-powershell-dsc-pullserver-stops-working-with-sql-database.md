---
title: "PowerShell DSC Pullserver stops working with SQL database"
url: "https://techcommunity.microsoft.com/t5/windows-server-for-it-pro/powershell-dsc-pullserver-stops-working-with-sql-database/m-p/4535199#M13076"
date: "2026-07-09"
author: "PatHel"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=WindowsServer"
---
After updating Windows Server 2025, our DSC Pull Server stopped communicating with its SQL backend database. The issue was not present before the update, and reverting to the previous version of Microsoft.PowerShell.DesiredStateConfiguration.Service.dll immediately restored normal functionality. With the newer DLL version, the service starts successfully and the endpoint remains available, but no connection is established to the SQL Server database.
