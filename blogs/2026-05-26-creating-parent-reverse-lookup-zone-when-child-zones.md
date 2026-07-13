---
title: "Creating parent reverse lookup zone when child zones already exist — what happens?"
url: "https://techcommunity.microsoft.com/t5/windows-server-for-it-pro/creating-parent-reverse-lookup-zone-when-child-zones-already/m-p/4522788#M13022"
date: "2026-05-26"
author: "pa5424847"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=WindowsServer"
---
We have an AD-integrated DNS environment that has accumulated a large number of reverse lookup zones over time, created without any parent zone — essentially DNS sprawl from years of admins creating individual subnet zones rather than working from a parent. We currently have approximately 80+ reverse lookup zones including: Dozens of x.10.in-addr.arpa zones covering various 10.x.x.x subnets Multiple x.172.in-addr.arpa zones A handful of others including 100.192.10.in-addr.arpa, 168.192.in-addr.arpa, 204.167.in-addr.arpa, 215.204.167.in-addr.arpa, 135.7.in-addr.arpa None of these were ever dele
