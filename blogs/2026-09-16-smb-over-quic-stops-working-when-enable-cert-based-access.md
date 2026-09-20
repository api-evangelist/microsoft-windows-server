---
title: "SMB over QUIC stops working when enable Cert based Access Control"
url: "https://techcommunity.microsoft.com/t5/windows-server-for-it-pro/smb-over-quic-stops-working-when-enable-cert-based-access/m-p/4557264#M13188"
date: "2026-09-16"
author: "Matthew Brice"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=WindowsServer"
---
Trying to test out SMB over QUIC so can eliminate need for vpn. When setting "Set-SmbServerCertificateMapping -RequireClientAuthentication $true" (enabling Access Control) client can no longer connect. "System error 67 has occurred.
