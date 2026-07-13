---
title: "AD Replication Error 1908 (Source DSA)"
url: "https://techcommunity.microsoft.com/t5/windows-server-for-it-pro/ad-replication-error-1908-source-dsa/m-p/4514064#M12997"
date: "2026-04-23"
author: "M_i_g_u_e_l"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=WindowsServer"
---
Hi all, I’m troubleshooting an Active Directory replication issue (error 1908 – “Could not find the domain controller”) in a multi-site environment with 16 domain controllers across multiple locations. The problematic Domain Controller (Site A-DC) is displaying a 6% failure in the replication summary with the 1908 error code in the Source DSA but the Destination DSA do not display any errors. If I replsummary in other DCs, I will see the same result.
