<div align="center">

<img src="https://avatars.githubusercontent.com/u/203710473?s=200&v=4" alt="Sertainty" width="100" />

# Sertainty SDK — Developers Edition

### Embed access controls directly into your data —<br>protection that travels with the file, everywhere it goes.

[![Latest release](https://img.shields.io/badge/Latest%20Release-4f46e5?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sertainty/Developer-V5/releases/latest)
[![Knowledge Base](https://img.shields.io/badge/Knowledge%20Base-4f46e5?style=for-the-badge&logo=readthedocs&logoColor=white)](https://sertainty.github.io/knowledge-base/)
[![Website](https://img.shields.io/badge/Website-sertainty.com-1e2327?style=for-the-badge&logo=googlechrome&logoColor=white)](https://www.sertainty.com/)

</div>

---

## Overview

> **Legacy versions sunset.** As of v5.0, Sertainty v4 and all earlier releases are end-of-life — no longer maintained, supported, or receiving updates or fixes. We recommend all users migrate to v5.0 or later.

> The **Developers Edition** provides the core Sertainty UXP libraries for building data-centric protection directly into your own applications. It is intended for the developer community to evaluate, prototype, and integrate UXP Technology.

> **Downloads are open — usage is licensed.** Anyone may download the SDK. Running it requires a separate Sertainty license (evaluation, development, or production). See [Licensing](#licensing).


## What's included

- Core UXP libraries
- Supported APIs (C++, C)
- API documentation
- Basic code examples
- Sertainty Technology Guide
- Knowledge Base (offline copy included in the build)
- Additional supported language wrappers

> **Note:** A snapshot of the Knowledge Base is bundled in each release for offline use. The most current Knowledge Base is always on GitHub — https://sertainty.github.io/knowledge-base/

For services, UXL scripting, and utility applications, see the **[Enterprise Edition](https://github.com/Sertainty/sdk-enterprise)**.

## Download

Get the latest binaries from the **[Releases page](https://github.com/Sertainty/Developer-V5/releases/latest)**. Each release lists the available platform packages along with a SHA-256 checksum for verification.

**Available for macOS, Windows, and Linux** — one package per platform in every release.

### Verify your download

```bash
# macOS / Linux
shasum -a 256 <downloaded-file>      # or: sha256sum <downloaded-file>

# Windows (PowerShell / cmd)
certutil -hashfile <downloaded-file> SHA256
```

Compare the result against the checksum published in the release notes.

## Quick start

<!-- TODO: replace with your actual package names and steps -->
1. Download the package for your platform from **Releases**.
2. Verify the SHA-256 checksum (above).
3. Extract the archive to your project's dependency location.
4. Link against the core UXP libraries — see the API documentation.
5. Apply your license file — see [Licensing](#licensing).

## Documentation

- **Knowledge Base:** https://sertainty.github.io/knowledge-base/
- **Sertainty Technology Guide:** included with each release <!-- TODO: add direct link if hosted -->
- **API reference:** <!-- TODO: add link -->

## Licensing

Downloading this SDK does **not** grant a right to use it in production. A separate Sertainty license is required:

| License | How to obtain |
| :--- | :--- |
| **Evaluation** (limited functionality / timeframe) or **Development** | [tech-support@sertainty.com](mailto:tech-support@sertainty.com) |
| **Production** license & pricing | [sales@sertainty.com](mailto:sales@sertainty.com) |

See the [`LICENSE`](./LICENSE) / EULA file for full terms. <!-- TODO: add an EULA file (see note in the handoff) -->

## Support & contact

- **Technical support & licenses:** tech-support@sertainty.com
- **Sales & business development:** sales@sertainty.com
- **Website:** https://www.sertainty.com/

---

<div align="center">

© Sertainty · UXP Technology · Protect your data at the source.

</div>
