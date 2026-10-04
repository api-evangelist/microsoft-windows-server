---
title: "Windows Server 2025 – DHCP Failover con dos controladores de dominio: el ámbito no se sincroniza"
url: "https://techcommunity.microsoft.com/t5/windows-server-for-it-pro/windows-server-2025-dhcp-failover-con-dos-controladores-de/m-p/4559692#M13226"
date: "2026-09-24"
author: "rjarosor01"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=WindowsServer"
---
Hola buenas a todos. Recientemente he configurado una implementación de DHCP Failover entre dos controladores de dominio con Windows Server 2025 (DC1 y DC2), utilizando el modo Hot Standby. La configuración del ámbito se replica correctamente después de la configuración inicial, pero después de realizar cualquier cambio manual en las opciones del ámbito (por ejemplo, modificar la puerta de enlace predeterminada o añadir una nueva reserva), los cambios no se sincronizan automáticamente con el servidor asociado.
