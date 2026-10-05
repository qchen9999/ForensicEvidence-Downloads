# Forensic Evidence Viewer downloads

Prebuilt desktop releases of **Forensic Evidence Viewer** by BBSoft LLC.

Visit [the product page](https://bbsoftllc.com/forensic-evidence/) for features and download instructions, or browse [Releases](https://github.com/qchen9999/ForensicEvidence-Downloads/releases).

## Version 0.3.6

| Platform | Requirements | Package |
| --- | --- | --- |
| Windows x64 | Windows 10 or later, Intel/AMD 64-bit | ZIP |
| Windows ARM64 | Windows 11, ARM64, x64 helper emulation; cross-build without ARM64 runtime testing | ZIP |
| Linux x64 | glibc 2.35 or later; Ubuntu 22.04 baseline | TAR.GZ |
| macOS Apple Silicon | macOS 14 or later, ARM64 | TAR.GZ |

Download the appropriate archive, extract it, and follow its README. Optional AI search requires a separate Ollama installation, locally or on a remote server, and the `gemma4:12b`, `nomic-embed-text` and selected picture-description models. The default picture model is `qwen3-vl:2b-instruct`; saved model choices are retained. Optional OCR requires separately installed model weights and configuration.

Windows packages are not publisher-signed. The macOS app is ad-hoc signed and is not Apple notarized; operating-system security checks may prevent it from opening.

Compare downloads against `SHA256SUMS.txt` supplied with the release.

## Third-party components

The binary packages include third-party license notices. The separate [dependency source release](https://github.com/qchen9999/ForensicEvidence-Downloads/releases/tag/dependencies-v0.3.6) supplies native dependency source, license texts, provenance, and rebuild materials, including libewf. These components retain their respective licenses and applicable replacement rights.

Version 0.3.6 adds HEIC/camera RAW support, pasted picture and document references
for AI search, persistent text search, optional OvisOCR2 integration, larger hover
previews, per-file indexing status, and recovery for a deleted case database.
Evidence browsing stays available during processing and AI search. Picture
descriptions have a separate model setting and four concurrent requests by default.
Optional SigLIP 2 categorization uses a separately deployed service and is disabled
by default.

This repository contains release information and prebuilt downloads, not the application's source code. GitHub's automatically generated source archives contain only this repository's release information.

Product support: [support@bbsoftllc.com](mailto:support@bbsoftllc.com).
