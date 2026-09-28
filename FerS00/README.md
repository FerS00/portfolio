# FerS00

Systems Engineering / Software Development

I build business applications end to end — Angular and Spring Boot web systems, Python
services with LLM tool calling, and native Windows tools in C++ and C# — with a focus on
security, licensing and keeping legacy systems working while they are modernized.

## Selected projects

### [OPERATIX](https://github.com/FerS00/OPERATIX)

Conversational agent that turns sales requests written in natural language into validated
transactions. The LLM only proposes tool arguments; the domain validates them and writes to
Excel, Google Sheets or MySQL, with idempotency keys, per-currency reports, a React
dashboard and a Telegram channel with explicit confirmation.

Python · FastAPI · LangChain / LangGraph · OpenAI, Anthropic, Gemini · SQLAlchemy · MySQL · React · Docker

**Public source**

### [WLQuickGen](https://github.com/FerS00/WLQuickGen)

Portable Win32 license generator for products protected with WinLicense. Auto-detects the
generator SDK and its architecture, writes licenses atomically, supports English, Spanish
and Portuguese, and exposes stable control IDs for UI automation with pywinauto.

C++17 · Win32 API · CMake · GitHub Actions

**Public source**

### [LICENSE-SERVICE](https://github.com/FerS00/portfolio/blob/main/projects/license-service/README.md)

Offline, device-bound licensing for .NET Windows applications: a packager wraps an
existing executable, the customer sends a hardware request code, and an issuer returns a
signed response. Licenses are signed with ECDSA P-256 and payloads use authenticated
encryption; issuing secrets never leave the issuer workstation.

C# · .NET 10 · Windows Forms · ECDSA P-256 · AES-GCM · Docker

**Private source — case study available**

### [VENTAS_DPP](https://github.com/FerS00/portfolio/blob/main/projects/ventas-dpp/README.md)

Storefront and back office for a software reseller, replacing a hosted store: catalog,
bundles, offers with price snapshots, customer accounts with one-time codes, permission-based
back office, notification outbox, spreadsheet catalog sync, XLSX/PDF exports and a guided
assistant with an optional LLM mode.

Angular 20 · Spring Boot 3.4 · Java 17 · Spring Security · Flyway · MariaDB/MySQL · Docker

**Private source — case study available**

### [Hwid-Keygen-Core](https://github.com/FerS00/portfolio/blob/main/projects/hwid-keygen-core/README.md)

Offline activation layer bound to a hardware ID for executables protected with WinLicense
when only the compiled `.exe` is available: a plugin runs before the application and checks
an ECDSA P-256 signed response produced on a separate issuer machine.

C++17 · Win32 · Windows CNG · CMake

**Private source — case study available**

## More

- Case studies of all private-source projects: [FerS00/portfolio](https://github.com/FerS00/portfolio)
