<p align="center">
  <img src="https://raw.githubusercontent.com/CompleteTech-Security/.github/main/profile/assets/banner.jpg" alt="CompleteTech Security" width="100%">
</p>

<div align="center">

# CompleteTech Security

**Evidence-first vulnerability assessment tools.** *Innovation at Every Integration.*

</div>

We build small, single-purpose checkers that compare evidence you supply (versions, inventories, headers, SBOMs) against documented advisories, and report what is potentially affected, what reports a fixed version, and what is unknown. They never claim exploitability and never treat "unknown" as "safe".

## What is here

| Portfolio | Repos |
|---|---:|
| Node.js CVE checkers | 20 |
| NetScaler CVE checkers | 10 |
| SonicWall SMA1000 checkers | 4 |
| Other application, dependency, and infrastructure checkers | 15 |
| Inventory and reporting utilities ([oci-runtime-inventory](https://github.com/CompleteTech-Security/oci-runtime-inventory), [scan-results-bridge](https://github.com/CompleteTech-Security/scan-results-bridge)) | 2 |

Good places to start: [php2shell-check](https://github.com/CompleteTech-Security/php2shell-check), [node2shell-check](https://github.com/CompleteTech-Security/node2shell-check), [scan-results-bridge](https://github.com/CompleteTech-Security/scan-results-bridge).

## Featured

<p>
  <a href="https://github.com/CompleteTech-Security/php2shell-check"><img src="https://raw.githubusercontent.com/CompleteTech-Security/.github/main/profile/assets/cards/php2shell-check.svg" alt="php2shell-check" width="400"></a>
  <a href="https://github.com/CompleteTech-Security/node2shell-check"><img src="https://raw.githubusercontent.com/CompleteTech-Security/.github/main/profile/assets/cards/node2shell-check.svg" alt="node2shell-check" width="400"></a>
  <a href="https://github.com/CompleteTech-Security/scan-results-bridge"><img src="https://raw.githubusercontent.com/CompleteTech-Security/.github/main/profile/assets/cards/scan-results-bridge.svg" alt="scan-results-bridge" width="400"></a>
</p>

## All projects

<details>
<summary><strong>Other application, dependency, and infrastructure checkers</strong> <sub>15</sub></summary>

| Repository | What it is | License |
|---|---|---|
| [atlassian-cve-2026-21589-check](https://github.com/CompleteTech-Security/atlassian-cve-2026-21589-check) | Offline Atlassian Data Center evidence checker for CVE-2026-21589. Self-managed product and version evidence. Standalone Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |
| [beyondtrust-remote-support-cve-2026-102764-check](https://github.com/CompleteTech-Security/beyondtrust-remote-support-cve-2026-102764-check) | Offline BeyondTrust Remote Support evidence checker for CVE-2026-102764. Remote Support version and configuration evidence. Standalone Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |
| [copyescape-check](https://github.com/CompleteTech-Security/copyescape-check) | Offline Docker CopyEscape evidence checker for CVE-2026-17106. Docker version and build-configuration evidence. Standalone Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |
| [docker-hub-ghostpat-check](https://github.com/CompleteTech-Security/docker-hub-ghostpat-check) | Offline Docker Hub PAT evidence checker for CVE-2026-105445. Supplied evidence only; no token collection, login or API requests. JSON/CSV/HTML reports. | See repository |
| [flowise-cve-2026-69254-check](https://github.com/CompleteTech-Security/flowise-cve-2026-69254-check) | Offline Flowise evidence checker for CVE-2026-69254. Flowise version and configuration evidence. Standalone Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |
| [fortimail-cve-2026-104286-check](https://github.com/CompleteTech-Security/fortimail-cve-2026-104286-check) | Offline FortiMail evidence checker for CVE-2026-104286. FortiMail version and deployment evidence. Standalone Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |
| [http2shell-check](https://github.com/CompleteTech-Security/http2shell-check) | Offline Brotli / HTTP2Shell (CVE-2026-111497) exposure and inventory checker across verified ecosystems. Python 3.10+, no dependencies or exploit payloads. | See repository |
| [ivanti-connect-secure-cve-2026-104935-check](https://github.com/CompleteTech-Security/ivanti-connect-secure-cve-2026-104935-check) | Offline Ivanti Connect Secure evidence checker for CVE-2026-104935. Connect Secure build and configuration evidence. Standalone Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |
| [nextjs-use-cache-rce-check](https://github.com/CompleteTech-Security/nextjs-use-cache-rce-check) | Offline Next.js use-cache evidence checker for GHSA-673q-mjm6-r5xr. Next.js cache and typed-array evidence. Standalone Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |
| [node2shell-check](https://github.com/CompleteTech-Security/node2shell-check) | Passive Node2Shell (CVE-2026-111497) exposure checker and offline Node.js runtime assessment with branded HTML reports. Python 3.10+, no dependencies, no exploit payloads. | See repository |
| [php2shell-check](https://github.com/CompleteTech-Security/php2shell-check) | Passive PHP2Shell (CVE-2026-109618, CVE-2026-109619) exposure checker with branded HTML reports. Single-file Python, no dependencies, no exploit payloads. | See repository |
| [sharp-vectorfreed-check](https://github.com/CompleteTech-Security/sharp-vectorfreed-check) | Offline Sharp / librsvg evidence checker for CVE-2026-96889. Sharp and librsvg version and build evidence. Standalone Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |
| [simple-git-rce-check](https://github.com/CompleteTech-Security/simple-git-rce-check) | Offline simple-git evidence checker for CVE-2026-102826. Git configuration and package evidence. Standalone Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |
| [tinypool-options-rce-check](https://github.com/CompleteTech-Security/tinypool-options-rce-check) | Offline Tinypool evidence checker for CVE-2026-104849. Worker-pool package and options evidence. Standalone Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |
| [vm2-nesting-check](https://github.com/CompleteTech-Security/vm2-nesting-check) | Offline vm2 evidence checker for CVE-2026-92935. Sandbox package and nesting evidence. Standalone Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |

</details>

<details>
<summary><strong>Node.js CVE checkers</strong> <sub>20</sub></summary>

| Repository | What it is | License |
|---|---|---|
| [node-cve-2026-105481-check](https://github.com/CompleteTech-Security/node-cve-2026-105481-check) | Offline Node.js evidence checker for CVE-2026-105481: HTTP keep-alive premature-response acceptance. Single-file Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |
| [node-cve-2026-105482-check](https://github.com/CompleteTech-Security/node-cve-2026-105482-check) | Offline Node.js evidence checker for CVE-2026-105482: DNS resolution NUL-name truncation. Single-file Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |
| [node-cve-2026-105483-check](https://github.com/CompleteTech-Security/node-cve-2026-105483-check) | Offline Node.js evidence checker for CVE-2026-105483: TLS fullwidth-IP hostname validation bypass. Single-file Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |
| [node-cve-2026-106069-check](https://github.com/CompleteTech-Security/node-cve-2026-106069-check) | Offline Node.js evidence checker for CVE-2026-106069: TLS leading-zero IPv4 resolver mismatch. Single-file Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |
| [node-cve-2026-106070-check](https://github.com/CompleteTech-Security/node-cve-2026-106070-check) | Offline Node.js evidence checker for CVE-2026-106070: ZipFile invalid-header content substitution. Single-file Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |
| [node-cve-2026-106071-check](https://github.com/CompleteTech-Security/node-cve-2026-106071-check) | Offline Node.js evidence checker for CVE-2026-106071: Permission Model wildcard path over-grant. Single-file Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |
| [node-cve-2026-106072-check](https://github.com/CompleteTech-Security/node-cve-2026-106072-check) | Offline Node.js evidence checker for CVE-2026-106072: TLS noncanonical-IP DNS SAN acceptance. Single-file Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |
| [node-cve-2026-106073-check](https://github.com/CompleteTech-Security/node-cve-2026-106073-check) | Offline Node.js evidence checker for CVE-2026-106073: Permission Model realpathSync read bypass. Single-file Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |
| [node-cve-2026-106074-check](https://github.com/CompleteTech-Security/node-cve-2026-106074-check) | Offline Node.js evidence checker for CVE-2026-106074: Crypto entropy cache duplication in snapshots. Single-file Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |
| [node-cve-2026-56846-check](https://github.com/CompleteTech-Security/node-cve-2026-56846-check) | Offline Node.js evidence checker for CVE-2026-56846: HTTP/2 retained header memory exhaustion. Single-file Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |
| [node-cve-2026-56847-check](https://github.com/CompleteTech-Security/node-cve-2026-56847-check) | Offline Node.js evidence checker for CVE-2026-56847: Permission Model trace-log filesystem bypass. Single-file Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |
| [node-cve-2026-56848-check](https://github.com/CompleteTech-Security/node-cve-2026-56848-check) | Offline Node.js evidence checker for CVE-2026-56848: HTTP/2 reentrant send use-after-free. Single-file Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |
| [node-cve-2026-56850-check](https://github.com/CompleteTech-Security/node-cve-2026-56850-check) | Offline Node.js evidence checker for CVE-2026-56850: HTTPS Agent PFX client identity collision. Single-file Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |
| [node-cve-2026-58039-check](https://github.com/CompleteTech-Security/node-cve-2026-58039-check) | Offline Node.js evidence checker for CVE-2026-58039: Permission Model process-report filesystem bypass. Single-file Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |
| [node-cve-2026-58040-check](https://github.com/CompleteTech-Security/node-cve-2026-58040-check) | Offline Node.js evidence checker for CVE-2026-58040: HTTPS Agent TLS session identity-policy bypass. Single-file Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |
| [node-cve-2026-58041-check](https://github.com/CompleteTech-Security/node-cve-2026-58041-check) | Offline Node.js evidence checker for CVE-2026-58041: SQLite cached iterator write replay. Single-file Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |
| [node-cve-2026-58042-check](https://github.com/CompleteTech-Security/node-cve-2026-58042-check) | Offline Node.js evidence checker for CVE-2026-58042: DNS resolveAny process abort. Single-file Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |
| [node-cve-2026-58043-check](https://github.com/CompleteTech-Security/node-cve-2026-58043-check) | Offline Node.js evidence checker for CVE-2026-58043: Permission Model path-prefix over-grant. Single-file Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |
| [node-cve-2026-58044-check](https://github.com/CompleteTech-Security/node-cve-2026-58044-check) | Offline Node.js evidence checker for CVE-2026-58044: HTTP header-limit request smuggling. Single-file Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |
| [node-cve-2026-58045-check](https://github.com/CompleteTech-Security/node-cve-2026-58045-check) | Offline Node.js evidence checker for CVE-2026-58045: zlib synchronous API spoofed TypedArray crash. Single-file Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |

</details>

<details>
<summary><strong>NetScaler CVE checkers</strong> <sub>10</sub></summary>

| Repository | What it is | License |
|---|---|---|
| [netscaler-cve-2026-19489-check](https://github.com/CompleteTech-Security/netscaler-cve-2026-19489-check) | Offline NetScaler ADC / Gateway evidence checker for CVE-2026-19489. Reported firmware and configuration evidence. Standalone Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |
| [netscaler-cve-2026-19490-check](https://github.com/CompleteTech-Security/netscaler-cve-2026-19490-check) | Offline NetScaler ADC / Gateway evidence checker for CVE-2026-19490. Reported firmware and configuration evidence. Standalone Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |
| [netscaler-cve-2026-88773-check](https://github.com/CompleteTech-Security/netscaler-cve-2026-88773-check) | Offline NetScaler ADC / Gateway evidence checker for CVE-2026-88773. Reported firmware and configuration evidence. Standalone Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |
| [netscaler-cve-2026-88774-check](https://github.com/CompleteTech-Security/netscaler-cve-2026-88774-check) | Offline NetScaler ADC / Gateway evidence checker for CVE-2026-88774. Reported firmware and configuration evidence. Standalone Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |
| [netscaler-cve-2026-88775-check](https://github.com/CompleteTech-Security/netscaler-cve-2026-88775-check) | Offline NetScaler ADC / Gateway evidence checker for CVE-2026-88775. Reported firmware and configuration evidence. Standalone Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |
| [netscaler-cve-2026-88776-check](https://github.com/CompleteTech-Security/netscaler-cve-2026-88776-check) | Offline NetScaler ADC / Gateway evidence checker for CVE-2026-88776. Reported firmware and configuration evidence. Standalone Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |
| [netscaler-cve-2026-88777-check](https://github.com/CompleteTech-Security/netscaler-cve-2026-88777-check) | Offline NetScaler ADC / Gateway evidence checker for CVE-2026-88777. Reported firmware and configuration evidence. Standalone Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |
| [netscaler-cve-2026-88778-check](https://github.com/CompleteTech-Security/netscaler-cve-2026-88778-check) | Offline NetScaler ADC / Gateway evidence checker for CVE-2026-88778. Reported firmware and configuration evidence. Standalone Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |
| [netscaler-pitscaler-cve-2026-88771-check](https://github.com/CompleteTech-Security/netscaler-pitscaler-cve-2026-88771-check) | Offline NetScaler ADC / Gateway evidence checker for CVE-2026-88771. Reported firmware and configuration evidence. Standalone Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |
| [netscaler-pitscaler-cve-2026-88772-check](https://github.com/CompleteTech-Security/netscaler-pitscaler-cve-2026-88772-check) | Offline NetScaler ADC / Gateway evidence checker for CVE-2026-88772. Reported firmware and configuration evidence. Standalone Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |

</details>

<details>
<summary><strong>SonicWall SMA1000 checkers</strong> <sub>4</sub></summary>

| Repository | What it is | License |
|---|---|---|
| [sonicwall-sma1000-cve-2026-102255-check](https://github.com/CompleteTech-Security/sonicwall-sma1000-cve-2026-102255-check) | Offline SonicWall SMA1000 evidence checker for CVE-2026-102255. Reported build and configuration evidence. Standalone Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |
| [sonicwall-sma1000-cve-2026-102256-check](https://github.com/CompleteTech-Security/sonicwall-sma1000-cve-2026-102256-check) | Offline SonicWall SMA1000 evidence checker for CVE-2026-102256. Reported build and configuration evidence. Standalone Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |
| [sonicwall-sma1000-cve-2026-102257-check](https://github.com/CompleteTech-Security/sonicwall-sma1000-cve-2026-102257-check) | Offline SonicWall SMA1000 evidence checker for CVE-2026-102257. Reported build and configuration evidence. Standalone Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |
| [sonicwall-sma1000-cve-2026-102258-check](https://github.com/CompleteTech-Security/sonicwall-sma1000-cve-2026-102258-check) | Offline SonicWall SMA1000 evidence checker for CVE-2026-102258. Reported build and configuration evidence. Standalone Python; JSON/CSV/HTML reports; no exploit payloads. | See repository |

</details>

<details>
<summary><strong>Inventory and reporting utilities</strong> <sub>2</sub></summary>

| Repository | What it is | License |
|---|---|---|
| [oci-runtime-inventory](https://github.com/CompleteTech-Security/oci-runtime-inventory) | Offline OCI/Docker-save and SBOM inventory with bounded parsing, digest provenance and consumer exports. No image execution, extraction or registry access. | See repository |
| [scan-results-bridge](https://github.com/CompleteTech-Security/scan-results-bridge) | Offline security-report converter to SARIF 2.1.0 and NDJSON with schema validation and preserved evidence provenance. No scanning or uploads. | See repository |

</details>

<details>
<summary><strong>Business plan template</strong> <sub>1</sub></summary>

| Repository | What it is | License |
|---|---|---|
| [business-plan](https://github.com/CompleteTech-Security/business-plan) | Create a company-neutral business plan for an AI-enabled security and technology services practice. | See repository |

</details>

## Build a business with it

We published our plan for turning tools like these into an AI-assisted services business, including a legal checklist and a guide for adapting it: **[Open business plan template](https://github.com/CompleteTech-Security/business-plan)**. It is a company-neutral template: use it, adapt it, and make money with it.

## Use responsibly

- Run tools only against systems you own or have **written permission** to test.
- Results are evidence for human review, not a guarantee of security or a substitute for a penetration test.
- Advisory data is dated; verify against current vendor advisories.
- Nothing here is legal, financial, or security advice, and nothing is a promise of income.

Most repositories are AGPL-3.0 with commercial licensing available; check each repository's license. The CompleteTech name and logo are not licensed for reuse.

[complete.tech](https://complete.tech)

<!-- showcase:footer:start -->
<p align="center">
  <a href="https://www.complete.tech">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/CompleteTech-LLC/.github/main/brand/logo-dark.png">
      <img src="https://raw.githubusercontent.com/CompleteTech-LLC/.github/main/brand/logo.png" alt="CompleteTech LLC" width="200">
    </picture>
  </a>
  <br>
  Built by <a href="https://www.complete.tech">CompleteTech LLC</a> · Innovation at Every Integration
</p>
<!-- showcase:footer:end -->
