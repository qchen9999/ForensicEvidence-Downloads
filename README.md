# Forensic Evidence Viewer downloads

Prebuilt Desktop and MCP releases of **Forensic Evidence Viewer** by BBSoft LLC.

Visit [the product page](https://bbsoftllc.com/forensic-evidence/) for features and download instructions, or open the [0.3.15 release](https://github.com/qchen9999/ForensicEvidence-Downloads/releases/tag/v0.3.15).

## Version 0.3.15

| Platform | Requirements | Packages |
| --- | --- | --- |
| Windows x64 | Intel/AMD 64-bit | Signed desktop MSI; signed Desktop and MCP ZIPs |
| Linux x64 | glibc 2.35 or later; Ubuntu 22.04 baseline | Desktop and MCP TAR.GZ archives |
| macOS Apple Silicon | macOS 14 or later, ARM64 | Desktop and MCP TAR.GZ app bundles |

For Windows, use the MSI installer or extract the complete portable ZIP. For Linux and macOS, extract the entire archive and follow its README. Windows payloads and the MSI are Authenticode signed by **BBSOFT LLC**. macOS app bundles are ad-hoc signed and are not Apple notarized. Dokany 2.x is a separate prerequisite for Windows read-only mounting. Windows ARM64, Linux ARM64 and Intel Mac packages are not included in this release.

Version 0.3.15 adds remote endpoint enrollment, agent package export, evidence browsing and collection; network/listener profiles; imported-image verification; persistent known-file hash libraries; and Volatility 3 memory-analysis execution and result views. The acquisition menu is now **Acquire Local Evidence…**. It also fixes Unix worker backpressure, concurrent Windows TLS-key cleanup and listener startup scanning the working directory. See the [release notes](https://github.com/qchen9999/ForensicEvidence-Downloads/releases/tag/v0.3.15) for details and validation limits.

**macOS endpoint logical-file collection remains experimental**, with unresolved source-open and continuous-containment limitations. Synthetic release checks do not establish privileged service/device lifecycle or separate-host physical-device acquisition.

Optional AI search, OCR and picture categorization require separately supplied runtimes, model weights or configuration. Volatility 3, Python and NSRL databases remain separate optional installations. See the package documentation for setup.

Compare downloads against their SHA-256 sidecars or `SHA256SUMS.txt` supplied with the release. Checksums verify file integrity; they do not replace publisher-signature verification.

## Third-party components

Binary packages retain third-party license notices. The separate [0.3.15 dependency-source release](https://github.com/qchen9999/ForensicEvidence-Downloads/releases/tag/dependencies-v0.3.15) supplies corresponding native dependency sources, license texts, provenance and reader rebuild materials. These components retain their respective licenses and applicable replacement rights. The companion's manifest records exact inputs and the documented historical APFS validation-test substitution.

This repository contains release information and prebuilt downloads, not Desktop/MCP application source. GitHub's automatically generated source archives contain only this repository's release information.

Product support: [support@bbsoftllc.com](mailto:support@bbsoftllc.com).
