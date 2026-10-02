# Forensic Evidence Viewer downloads

Prebuilt desktop releases of **Forensic Evidence Viewer** by BBSoft LLC.

Visit [the product page](https://bbsoftllc.com/forensic-evidence/) for features and download instructions, or browse [Releases](https://github.com/qchen9999/ForensicEvidence-Downloads/releases).

## Version 0.3.5

| Platform | Requirements | Package |
| --- | --- | --- |
| Windows x64 | Windows 10 or later, Intel/AMD 64-bit | ZIP |
| Linux x64 | glibc 2.35 or later; Ubuntu 22.04 baseline | TAR.GZ |
| macOS Apple Silicon | macOS 14 or later, ARM64 | TAR.GZ |

Download the appropriate archive, extract it, and follow its README. Optional AI search requires a separate local installation of Ollama and the `gemma4:12b` and `nomic-embed-text` models.

Windows packages are not publisher-signed. The macOS app is ad-hoc signed and is not Apple notarized; operating-system security checks may prevent it from opening.

Compare downloads against `SHA256SUMS.txt` supplied with the release.

## Third-party components

The binary packages include third-party license notices. The separate [dependency source release](https://github.com/qchen9999/ForensicEvidence-Downloads/releases/tag/dependencies-v0.3.5) supplies native dependency source, license texts, provenance, and rebuild materials, including libewf. These components retain their respective licenses and applicable replacement rights.

Version 0.3.5 adds PDF forensic reports, concurrent local AI picture descriptions,
configurable duplicate picture reuse, and AI performance regression benchmarks.
OvisOCR2 development is on a separate branch and is excluded from this release.

This repository contains release information and prebuilt downloads, not the application's source code. GitHub's automatically generated source archives contain only this repository's release information.

Product support: [support@bbsoftllc.com](mailto:support@bbsoftllc.com).
