<p align="center">
  <img src="https://avatars.githubusercontent.com/u/332581433?s=200&v=4" width="120" alt="retorrent logo">
</p>

<h1 align="center">retorrent</h1>

<p align="center">
  <b>The *arr stack, rethought.</b><br>
  One coherent system instead of six loosely coupled ones. Engineered like it's 2026.
</p>

---

## What is this?

retorrent is an open-source engineering project exploring what a **modern media automation stack** looks like when designed from scratch today: library management, metadata, indexing, download orchestration and the BitTorrent protocol itself.

The current ecosystem grew organically over a decade: separate services per media type, duplicated config, brittle inter-service APIs and slow evolution. We want to study and rebuild it as a single, well-architected product.

### Goals

- **One system, not a constellation**: shared data model, shared config, one API.
- **Performance and reliability first**: Rust-first core, typed contracts, observable by default.
- **Modern ops**: container-native, sane defaults, declarative configuration.
- **Clean protocol work**: a readable, well-tested BitTorrent / DHT implementation to learn from.
- **Documented design**: ADRs and write-ups so the *why* is as useful as the *what*.

### Status

🚧 Early stage. Architecture and design work in progress. Nothing here is production-ready.

---

## ⚖️ Legal notice & disclaimer

**Please read this section before using, forking or contributing to any repository in this organization.**

### Educational purpose

All projects published under the retorrent organization are developed **strictly for educational and research purposes**: studying software architecture, distributed systems, networking protocols and media library management.

### No support for piracy

retorrent **does not support, encourage or facilitate copyright infringement in any way.**

- The BitTorrent protocol is a neutral, lawful file-distribution technology, widely used for Linux distributions, open datasets, public-domain and Creative Commons works, game patches and more.
- **Downloading, sharing or distributing copyrighted works without the rights holder's authorization is illegal** in most jurisdictions and is **explicitly not an intended use** of this software.
- Issues, discussions or pull requests aimed at facilitating piracy (e.g. integrating or promoting infringing indexers or sources) will be closed and may result in a ban.

### Your content, your responsibility

- You must only use this software with content you **legally own or are authorized to access**: works you have purchased a legitimate copy of, content under a permissive license, or works in the public domain.
- Where applicable law provides a private-copy exception, it generally requires that the copy be made **from a lawfully acquired source**. A copy obtained from an unauthorized source is not covered.
- You are **solely responsible** for how you use this software and for complying with the laws of your country, including copyright and intellectual property law.

### No content hosted or provided

retorrent **does not host, index, link to or distribute any copyrighted content.** No repository in this organization ships with, or points by default to, any source of infringing material. The software only provides tooling; it contains no media.

### No warranty, no liability

All software is provided **"as is", without warranty of any kind**, as described in each repository's license. The authors and contributors **cannot be held liable** for any misuse of the software or for any damage resulting from its use.

---

<p align="center"><sub>Built for learning. Use responsibly.</sub></p>
