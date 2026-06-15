# Microsoft Windows Server (microsoft-windows-server)

APIs and integration points for Microsoft Windows Server operating system including management, networking, storage, virtualization, security, and remote administration capabilities for enterprise server infrastructure.

**APIs.json:** [https://www.microsoft.com/windows-server](https://www.microsoft.com/windows-server)

## Scope

- **Type:** Index

## Tags

- Datacenter
- Enterprise
- Infrastructure
- Microsoft
- Operating System
- Server Management
- Windows Server
- Windows Server 2025

## Timestamps

- **Created:** 2024
- **Modified:** 2026-05-19

## APIs

### Windows Server Management API

PowerShell and WMI-based management APIs for Windows Server administration.

- **Human URL:** [https://docs.microsoft.com/windows-server/administration/](https://docs.microsoft.com/windows-server/administration/)
- **Base URL:** `https://localhost`

#### Tags

- Administration
- Management
- PowerShell
- WMI

#### Properties

- [Documentation](https://docs.microsoft.com/powershell/windows/get-started)
- [Postman Collection](collections/iis-administration-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/iis-administration-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Windows Remote Management (WinRM)

WS-Management protocol implementation for remote management of Windows servers using SOAP-based web services for configuration and operations.

- **Human URL:** [https://docs.microsoft.com/windows/win32/winrm/portal](https://docs.microsoft.com/windows/win32/winrm/portal)
- **Base URL:** `http://localhost:5985`

#### Tags

- PowerShell Remoting
- Remote Management
- SOAP
- WS-Management

#### Properties

- [Documentation](https://docs.microsoft.com/windows/win32/winrm/windows-remote-management-portal)
- [Postman Collection](collections/iis-administration-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/iis-administration-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Active Directory Domain Services API

LDAP and REST APIs for Active Directory management and authentication.

- **Human URL:** [https://docs.microsoft.com/windows-server/identity/ad-ds/](https://docs.microsoft.com/windows-server/identity/ad-ds/)
- **Base URL:** `ldap://localhost:389`

#### Tags

- Active Directory
- Authentication
- Directory Services
- LDAP

#### Properties

- [Documentation](https://docs.microsoft.com/windows/win32/ad/active-directory-domain-services)
- [SDK](https://docs.microsoft.com/dotnet/api/system.directoryservices)
- [Postman Collection](collections/iis-administration-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/iis-administration-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hyper-V Management API

APIs for managing Hyper-V virtualization platform including virtual machines, virtual switches, and virtual storage.

- **Human URL:** [https://docs.microsoft.com/virtualization/hyper-v-on-windows/](https://docs.microsoft.com/virtualization/hyper-v-on-windows/)
- **Base URL:** `https://localhost`

#### Tags

- Hyper-V
- Virtual Machines
- Virtualization

#### Properties

- [Documentation](https://docs.microsoft.com/virtualization/api/)
- [Postman Collection](collections/iis-administration-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/iis-administration-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Windows Server Update Services (WSUS) API

APIs for managing Windows updates across enterprise environments.

- **Human URL:** [https://docs.microsoft.com/windows-server/administration/windows-server-update-services/](https://docs.microsoft.com/windows-server/administration/windows-server-update-services/)
- **Base URL:** `https://localhost:8530`

#### Tags

- Patch Management
- Updates
- WSUS

#### Properties

- [Documentation](https://docs.microsoft.com/previous-versions/windows/desktop/aa354519(v=vs.85))
- [SDK](https://docs.microsoft.com/dotnet/api/microsoft.updateservices.administration)
- [Postman Collection](collections/iis-administration-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/iis-administration-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Windows Admin Center API

Modern web-based management interface REST API for Windows Server that provides a gateway service for relaying commands and scripts to managed nodes.

- **Human URL:** [https://docs.microsoft.com/windows-server/manage/windows-admin-center/](https://docs.microsoft.com/windows-server/manage/windows-admin-center/)
- **Base URL:** `https://localhost:6516`

#### Tags

- Admin Center
- Gateway
- REST API
- Web Management

#### Properties

- [Documentation](https://docs.microsoft.com/windows-server/manage/windows-admin-center/extend/extensibility-overview)
- [GitHub Repository](https://github.com/Microsoft/windows-admin-center-sdk)
- [Postman Collection](collections/iis-administration-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/iis-administration-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### DNS Server Management API

APIs for managing Windows DNS Server services.

- **Human URL:** [https://docs.microsoft.com/windows-server/networking/dns/](https://docs.microsoft.com/windows-server/networking/dns/)
- **Base URL:** `https://localhost`

#### Tags

- DNS
- Name Resolution
- Networking

#### Properties

- [Documentation](https://docs.microsoft.com/powershell/module/dnsserver/)
- [Postman Collection](collections/iis-administration-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/iis-administration-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Windows Management Instrumentation (WMI) API

Infrastructure for management data and operations on Windows-based operating systems providing COM, scripting, and .NET APIs for system administration and monitoring.

- **Human URL:** [https://learn.microsoft.com/en-us/windows/win32/wmisdk/wmi-start-page](https://learn.microsoft.com/en-us/windows/win32/wmisdk/wmi-start-page)
- **Base URL:** `https://localhost`

#### Tags

- COM
- Management
- Monitoring
- Scripting
- WMI

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/windows/win32/wmisdk/wmi-start-page)
- [API Reference](https://learn.microsoft.com/en-us/windows/win32/wmisdk/com-api-for-wmi)
- [Postman Collection](collections/iis-administration-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/iis-administration-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### IIS Administration API

REST API for managing Internet Information Services (IIS) web servers that enables configuration and monitoring from any HTTP client.

- **Human URL:** [https://learn.microsoft.com/en-us/iis-administration/](https://learn.microsoft.com/en-us/iis-administration/)
- **Base URL:** `https://localhost:55539`

#### Tags

- IIS
- REST API
- Web Management
- Web Server

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/iis-administration/)
- [Getting Started](https://learn.microsoft.com/en-us/iis-administration/getting-started)
- [GitHub Repository](https://github.com/microsoft/IIS.Administration)
- [OpenAPI](openapi/iis-administration-api.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/iis-administration-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/iis-administration-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Remote Desktop Services API

Win32 API for managing Remote Desktop Services including session management, virtual channels, user configuration, and the Remote Desktop Protocol.

- **Human URL:** [https://learn.microsoft.com/en-us/windows/win32/termserv/terminal-services-portal](https://learn.microsoft.com/en-us/windows/win32/termserv/terminal-services-portal)
- **Base URL:** `https://localhost`

#### Tags

- RDS
- Remote Access
- Remote Desktop
- Terminal Services

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/windows/win32/termserv/terminal-services-portal)
- [API Reference](https://learn.microsoft.com/en-us/windows/win32/termserv/terminal-services-api-reference)
- [Postman Collection](collections/iis-administration-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/iis-administration-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Failover Clustering API

APIs for defining and managing software and hardware components on failover clusters to increase application scalability and availability.

- **Human URL:** [https://learn.microsoft.com/en-us/windows-server/failover-clustering/failover-clustering-overview](https://learn.microsoft.com/en-us/windows-server/failover-clustering/failover-clustering-overview)
- **Base URL:** `https://localhost`

#### Tags

- Cluster Management
- Failover Clustering
- High Availability

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/windows-server/failover-clustering/failover-clustering-overview)
- [API Reference](https://learn.microsoft.com/en-us/previous-versions/windows/desktop/mscs/failover-cluster-apis-portal)
- [Postman Collection](collections/iis-administration-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/iis-administration-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### DHCP Server Management API

APIs and PowerShell cmdlets for managing Dynamic Host Configuration Protocol server services including leases, reservations, and scopes.

- **Human URL:** [https://learn.microsoft.com/en-us/windows-server/networking/technologies/dhcp/dhcp-deploy-wps](https://learn.microsoft.com/en-us/windows-server/networking/technologies/dhcp/dhcp-deploy-wps)
- **Base URL:** `https://localhost`

#### Tags

- DHCP
- IP Address Management
- Networking

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/previous-versions/windows/desktop/dhcp/dhcp-server-management-api)
- [Postman Collection](collections/iis-administration-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/iis-administration-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SMB File Server API

Server Message Block protocol APIs and WMI management classes for managing file shares, share access, and network file sharing across Windows Server environments.

- **Human URL:** [https://learn.microsoft.com/en-us/windows-server/storage/file-server/file-server-smb-overview](https://learn.microsoft.com/en-us/windows-server/storage/file-server/file-server-smb-overview)
- **Base URL:** `https://localhost`

#### Tags

- File Sharing
- Network Storage
- SMB
- Storage

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/windows-server/storage/file-server/file-server-smb-overview)
- [Postman Collection](collections/iis-administration-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/iis-administration-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Windows Event Log API

API for instrumenting, querying, and consuming event logs on Windows Server for diagnostics, monitoring, and auditing.

- **Human URL:** [https://learn.microsoft.com/en-us/windows/win32/wes/windows-event-log](https://learn.microsoft.com/en-us/windows/win32/wes/windows-event-log)
- **Base URL:** `https://localhost`

#### Tags

- Diagnostics
- Event Log
- Logging
- Monitoring

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/windows/win32/wes/windows-event-log)
- [API Reference](https://learn.microsoft.com/en-us/windows/win32/wes/windows-event-log-reference)
- [Postman Collection](collections/iis-administration-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/iis-administration-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Storage Spaces Direct API

APIs and PowerShell management for software-defined storage enabling clustering of servers with internal storage for hyper-converged infrastructure.

- **Human URL:** [https://learn.microsoft.com/en-us/windows-server/storage/storage-spaces/storage-spaces-direct-overview](https://learn.microsoft.com/en-us/windows-server/storage/storage-spaces/storage-spaces-direct-overview)
- **Base URL:** `https://localhost`

#### Tags

- Hyper-Converged
- Software-Defined Storage
- Storage
- Storage Spaces Direct

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/windows-server/storage/storage-spaces/storage-spaces-direct-overview)
- [Postman Collection](collections/iis-administration-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/iis-administration-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Network Policy Server (NPS) RADIUS API

Network Policy Server providing centralized RADIUS authentication, authorization, and accounting for wireless, VPN, and dial-up connections.

- **Human URL:** [https://learn.microsoft.com/en-us/windows-server/networking/technologies/nps/nps-top](https://learn.microsoft.com/en-us/windows-server/networking/technologies/nps/nps-top)
- **Base URL:** `https://localhost`

#### Tags

- Authentication
- Network Access
- NPS
- RADIUS
- VPN

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/windows-server/networking/technologies/nps/nps-top)
- [Postman Collection](collections/iis-administration-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/iis-administration-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://portal.azure.com)
- [Documentation](https://docs.microsoft.com/windows-server/)
- [Support](https://support.microsoft.com/windows-server)
- [Blog](https://techcommunity.microsoft.com/t5/windows-server/bg-p/WindowsServer)
- [Terms of Service](https://www.microsoft.com/licensing/terms/)
- [Release Notes](https://learn.microsoft.com/en-us/windows-server/get-started/whats-new-windows-server-2025)
- [Privacy Policy](https://privacy.microsoft.com/privacystatement)
- [GitHub Repository](https://github.com/MicrosoftDocs/windowsserverdocs)
- [Security](https://learn.microsoft.com/en-us/windows-server/security/tls/tls-ssl-schannel-ssp-overview)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Integrations](https://www.microsoft.com/en-us/marketplace)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
