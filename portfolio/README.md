# Portfolio — FerS00

Case studies of projects whose source code is private. Each page describes the problem,
the architecture at a high level, the technical decisions and the current state, based on
the actual private repository. No proprietary source code, credentials, customer data or
security-sensitive implementation details are published here.

Projects with public source code are linked from the
[GitHub profile](https://github.com/FerS00).

## Private-source projects

| Project | Summary | Stack | State |
|---|---|---|---|
| [LICENSE-SERVICE](projects/license-service/README.md) | Offline, device-bound licensing for .NET Windows applications | C#, .NET 10, WinForms, ECDSA P-256, AES-GCM | Implemented; internal use |
| [Hwid-Keygen-Core](projects/hwid-keygen-core/README.md) | Offline HWID activation layer for executables protected with WinLicense | C++17, Win32, CNG (ECDSA P-256), CMake | Core implemented; Windows acceptance pending |
| [VENTAS_DPP](projects/ventas-dpp/README.md) | Storefront and back office for a software reseller | Angular 20, Spring Boot 3.4, Java 17, MariaDB/MySQL, Flyway, Docker | Most phases delivered; not deployed to production |
| [WEB-VENTA-DE-LICITACIONES](projects/web-venta-de-licitaciones/README.md) | Public catalog, internal sales/accounting operations and a public-procurement radar | Angular 21, Spring Boot 3.5, Java 17, MariaDB, Flyway, Docker | V1 delivered for local use |
| [GestionServicioDPP](projects/gestion-servicio-dpp/README.md) | Incremental hardening of a legacy PHP service-management application | PHP 8.2, PDO, MariaDB, Apache, Docker | In progress (phased modernization) |
| [Firma-DPP](projects/firma-dpp/README.md) | Desktop tool that records a technical "signature" of an installed PC | C#, .NET Framework 4.7.2, WinForms, WMI | v1.0.0 released internally |
| [FirmaDigital](projects/firma-digital/README.md) | Configurable generator of signer/reader apps with authenticated encryption | C#, .NET 10, WinForms, AES-256-GCM, PBKDF2 | Implemented |

## Why the code is private

Depending on the project, the source code is not published because it contains one or
more of the following: licensing and activation mechanisms whose publication would make
them easier to attack, a client's brand, catalog or operational configuration, personal or
business data used during development, or integrations with commercial SDKs that cannot be
redistributed.

> Source code is private due to security and intellectual-property considerations.

## License

The text of this repository is © 2026 FerS00, all rights reserved. See [LICENSE](LICENSE).
