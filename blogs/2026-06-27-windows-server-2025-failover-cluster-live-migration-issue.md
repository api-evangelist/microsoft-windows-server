---
title: "Windows Server 2025 Failover Cluster Live Migration Issue"
url: "https://techcommunity.microsoft.com/t5/windows-server-for-it-pro/windows-server-2025-failover-cluster-live-migration-issue/m-p/4531427#M13048"
date: "2026-06-27"
author: "madushan_gunarathne"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=WindowsServer"
---
Hi Everyone, I am facing an issue in a Hyper-V Failover Cluster environment where Live Migration intermittently fails due to a service logon-related problem. The environment was previously working normally, but now whenever we attempt to Live Migrate a VM between cluster nodes, the migration fails unless we manually run “gpupdate /force” on the Hyper-V host first. After running gpupdate /force, the migration works temporarily, but the issue returns again during the next migration attempt.
