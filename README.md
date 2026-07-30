# Hi, I'm Diogo Wermann

[English](README.md) | [Português](README.pt-BR.md)

**IT Analyst focused on infrastructure automation, endpoint management, hybrid identity, and cybersecurity.**

I build production-oriented tools for Microsoft environments, with an emphasis on safe automation, least privilege, observable operations, and reversible deployments. My current work spans Windows Server, Active Directory, Microsoft Entra ID, Intune, PowerShell, Python, Linux infrastructure, APIs, monitoring, and internal business systems.

I am currently studying **Systems Analysis and Development** and developing deeper expertise in **cybersecurity, cloud identity, and endpoint security**.

## Areas of Focus

- Microsoft Intune and enterprise endpoint management
- Active Directory and Microsoft Entra hybrid identity
- PowerShell automation and Windows administration
- Python APIs, operational dashboards, and monitoring
- Linux servers, virtualization, backup, and observability
- Security engineering, least privilege, and controlled rollout design

## Featured Projects

| Project | Description | Engineering focus |
|---|---|---|
| [DeviceLifecycle](https://github.com/diogowermann/DeviceLifecycle) | PowerShell automation for identifying, reporting, quarantining, and removing stale devices across Active Directory, Microsoft Entra ID, and Intune. | Identity correlation, safe state transitions, bounded actions, auditability, recovery |
| [DeviceLifecycle-API](https://github.com/diogowermann/DeviceLifecycle-API) | Read-only FastAPI extension that securely publishes the latest DeviceLifecycle reports, logs, metadata, and health information. | API design, authentication, stable file reads, network restrictions, operational integration |
| [WallpaperAgent](https://github.com/diogowermann/WallpaperAgent) | Windows agent that retrieves a versioned manifest, validates assets with SHA-256, and applies desktop and lock-screen images through Intune-managed deployment. | Privilege separation, content integrity, atomic promotion, endpoint packaging, rollback |
| [RustDeskIntuneDeployment](https://github.com/diogowermann/RustDeskIntuneDeployment) | PowerShell workflow for deploying and configuring RustDesk through Microsoft Intune in self-hosted environments. | Win32 application deployment, multi-profile configuration, detection, server trust, rollout governance |

## Technical Stack

### Automation and development

![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?logo=powershell&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?logo=mysql&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)

### Infrastructure and platforms

![Microsoft Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?logo=microsoftazure&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D4?logo=windows&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?logo=grafana&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)

## How I Approach Engineering

- **Fail safely:** missing or ambiguous data must not trigger destructive actions.
- **Automate with limits:** privileged operations require explicit scope, thresholds, and action caps.
- **Design for recovery:** quarantine, rollback, diagnostics, and audit trails are part of the implementation.
- **Separate responsibilities:** machine context, user context, publishing systems, and consumers receive only the access they require.
- **Document operational reality:** architecture, deployment, security boundaries, and failure modes are treated as part of the product.

## Current Direction

I am expanding from infrastructure and automation into cybersecurity, with particular interest in:

- identity and access security;
- endpoint security and hardening;
- security monitoring and incident response;
- secure automation and infrastructure engineering;
- cloud and hybrid-environment security.

## Languages

- Portuguese: native
- English: advanced

---

Most projects in this profile are based on real operational problems, and maybe some personal projects I'd like to share. Organization-specific identifiers, credentials, addresses, certificates, and other sensitive information are removed or replaced before publication.
