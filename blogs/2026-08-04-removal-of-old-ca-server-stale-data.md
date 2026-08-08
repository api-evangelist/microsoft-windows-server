---
title: "Removal of old CA server stale data"
url: "https://techcommunity.microsoft.com/t5/windows-server-for-it-pro/removal-of-old-ca-server-stale-data/m-p/4543768#M13112"
date: "2026-08-04"
author: "ben_2"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=WindowsServer"
---
Hi, I'm rebuilding some DC's and figured I'd tidy everything up before doing so as I've come into this with a messy environment. from this, I found an old Trusted Root CA, the certificate authority server was decommissioned in 2021 and all certificates have had an expiry date from 2021. its still being pushed out to domain devices such as servers and desktops.
