# Portfolio — Fernando Morales
**Web:** [fextracode.com](https://fextracode.com) · [Profile](https://github.com/FerS00) · [Case studies](#case-studies) · [Public projects](#public-source-projects) · [Contact](#contact)

**Case studies of private-source systems: licensing, commerce back offices and Windows tooling**  
*Problem, architecture, security model and trade-offs of each project, based on the real private repositories and without publishing proprietary code.*

![Projects](https://img.shields.io/badge/case%20studies-7-blue?style=flat-square)
![Java](https://img.shields.io/badge/Java-Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-20%20%7C%2021-DD0031?style=flat-square&logo=angular&logoColor=white)
![C#](https://img.shields.io/badge/C%23-.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-Win32-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-8.2-777BB4?style=flat-square&logo=php&logoColor=white)

---

### Overview
> Each page documents what the system does, how it is structured and which engineering decisions shaped it. Source code, credentials, customer data and implementation details that would weaken a protection mechanism are deliberately left out. Public-source projects are listed below and linked from the [GitHub profile](https://github.com/FerS00).

---

### Case Studies
| Project | Problem solved | Stack | State |
| :--- | :--- | :--- | :--- |
| [LICENSE-SERVICE](projects/license-service/README.md) | Offline, device-bound licensing for existing .NET executables | `C#` `.NET 10` `ECDSA P-256` `AES-GCM` | Implemented · internal use |
| [Hwid-Keygen-Core](projects/hwid-keygen-core/README.md) | Signed HWID activation for protected executables without source | `C++17` `Win32` `CNG` `CMake` | Core implemented · Windows acceptance pending |
| [VENTAS_DPP](projects/ventas-dpp/README.md) | Storefront + permission-based back office for a software reseller | `Angular 20` `Spring Boot 3.4` `Flyway` `MariaDB/MySQL` | Most phases delivered · not in production |
| [WEB-VENTA-DE-LICITACIONES](projects/web-venta-de-licitaciones/README.md) | Sales/accounting operations + public-procurement radar on OCDS data | `Angular 21` `Spring Boot 3.5` `MariaDB` `Docker` | V1 delivered for local use |
| [GestionServicioDPP](projects/gestion-servicio-dpp/README.md) | Security hardening of a legacy PHP app kept in daily use | `PHP 8.2` `PDO` `MariaDB` `Docker` | Phased modernization in progress |
| [Firma-DPP](projects/firma-dpp/README.md) | Installation record + hardware inventory for serviced PCs | `C#` `.NET Framework 4.7.2` `WMI` | v1.0.0 internal |
| [FirmaDigital](projects/firma-digital/README.md) | Config-driven signer/reader apps with authenticated encryption | `C#` `.NET 10` `AES-256-GCM` `PBKDF2` | Implemented |

---

### Public-Source Projects
| Project | What it does | Stack |
| :--- | :--- | :--- |
| [RelayForge](https://github.com/FerS00/RelayForge) | Self-hosted work console for Claude Code, Codex, and Antigravity with worktree isolation and human-approved delivery | `Python` `FastAPI` `React` `TypeScript` `SQLite` `Tailscale` |
| [Overseer](https://github.com/FerS00/Overseer) | Local, read-only real-time monitor for Claude Code and Codex with animated mascots | `Java 21` `Spring Boot 3.5` `Angular 22` `Node.js 24` `SSE` |
| [OPERATIX](https://github.com/FerS00/OPERATIX) | Sales assistant that turns natural-language requests into validated transactions | `Python` `FastAPI` `LangGraph` `MySQL` `React` |
| [WLQuickGen](https://github.com/FerS00/WLQuickGen) | Portable Win32 license generator for WinLicense-protected software | `C++17` `Win32 API` `CMake` |
| [VantageEngine](https://github.com/FerS00/VantageEngine) | White-label commerce engine with tenant-scoped theme, content and feature flags (planning stage) | `Java 21` `Spring Modulith` `Angular` `MySQL` |

---

### Recurring Engineering Themes
- **Offline trust:** activation and record flows that work without a server, using asymmetric signatures so distributed binaries cannot issue licenses.
- **Authorization at the boundary:** HttpOnly session cookies + CSRF, permission-based RBAC enforced server-side; the UI only hides actions.
- **Transactional integrity:** outbox notifications, idempotency keys, price snapshots and forward-only migrations.
- **Incremental modernization:** hardening live legacy systems in small, reversible, verified batches.
- **Honest security scope:** each case study states what the mechanism does *not* protect against.

---

### Why the Code Is Private
Depending on the project: licensing/activation mechanisms whose publication would make them easier to attack, a client's brand, catalog or operational configuration, data used during development, or integrations with commercial SDKs that cannot be redistributed.

> Source code is private due to security and intellectual-property considerations.

---

### Contact
- **Website:** [fextracode.com](https://fextracode.com)
- **GitHub:** [@FerS00](https://github.com/FerS00)
- **LinkedIn:** [Fernando Morales](https://linkedin.com/in/fernando-trinidad-morales-pe%C3%B1a-3632b2391)
- **Email:** [moralespenafernando@gmail.com](mailto:moralespenafernando@gmail.com)

---

### License
Text © 2026 FerS00, all rights reserved — see [LICENSE](LICENSE). No source code of the described projects is included.

**Author:** [FerS00](https://github.com/FerS00)
