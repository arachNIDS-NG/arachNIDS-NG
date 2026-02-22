# arachNIDS-NG

<div align="center">

[![Status](https://img.shields.io/badge/Status-In_Development-orange.svg)]()
[![Offline](https://img.shields.io/badge/Privacy-100%25_Offline-green.svg)]()
[![License](https://img.shields.io/badge/License-MIT%20-blue.svg)]()
[![Rust](https://img.shields.io/badge/Built_with-Rust-orange.svg)](https://www.rust-lang.org/)

**Modern, offline IDS signature management toolkit for Snort and Suricata**

*Reviving the arachNIDS signature archive — rebuilt for the modern DevSecOps*


---

</div>

## What is arachNIDS-NG?

**arachNIDS-NG** (Next Generation) is a comprehensive CLI toolkit for managing, validating, and deploying IDS signatures across enterprise environments. Built in Rust for performance and reliability, it brings signature-based intrusion detection into the Infrastructure-as-Code era.

### The Legacy

**arachNIDS** (Advanced Reference Archive of Current Heuristics for Network Intrusion Detection Systems) was a pioneering community-driven signature database created in the early 2000s. It served as the de facto reference for IDS signatures during the formative years of network security, providing curated detection rules primarily for Snort and contributing significantly to the standardization of signature-based intrusion detection.

### The Revival

While the original arachNIDS was a signature database, **arachNIDS-NG** evolves this concept into a complete lifecycle management platform for modern security operations:

---

## Why Rust?

**Performance:**
- 10-100x faster than Python 
- Native compilation for zero overhead abstractions
- Efficient memory usage for large rulesets

**Safety:**
- Memory safe by default (no buffer overflows)
- Concurrent processing without data races
- Prevents entire classes of security vulnerabilities

**Deployment:**
- Single static binary, no dependencies
- Cross-platform without runtime requirements
- Minimal attack surface

**Ecosystem:**
- Awesome parser combinator libraries
- First-class CLI tooling (clap)
- Strong SQLite integration (rusqlite)

---

## FAQ

### When will the first release be available?

We're targeting an **alpha release in Q1 2026**. Follow this repository for updates.

### Will this replace Pulledpork or Suricata-Update?

No, arachNIDS-NG serves a different purpose. Those tools focus on downloading and managing vendor-provided rulesets. arachNIDS-NG focuses on creating, testing, and managing **your own custom signatures** with a modern workflow.

### Can I use this in production?

Not yet. The project is in active development. Production-ready releases will be clearly marked.

### What happened to the original arachNIDS?

The original arachNIDS database was maintained until the mid-2000s. This project honors that legacy by bringing the concept of a comprehensive signature management system into the modern era.

### Will there be a hosted service?

No. arachNIDS-NG is **offline-first by design**. We may provide a public signature repository for download, but the core tool will always work completely offline.

### Can I help with development?

Not yet, but soon! We'll open up contributions once we reach alpha. Until then, star the repo and share your requirements via GitHub issues.

---

## Support

If you find this project useful, consider supporting my work:

<a href="https://buymeacoffee.com/webmoney" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" height="40"></a>

**Crypto donations:**
- <a href="bitcoin:bc1quavqz6cxqzfy4qtvq4zxc4fjgap3s7cmxja0k4"><img src="https://img.shields.io/badge/Bitcoin-000000?style=plastic&logo=bitcoin&logoColor=white" alt="Bitcoin"></a> `bc1quavqz6cxqzfy4qtvq4zxc4fjgap3s7cmxja0k4`
- <a href="ethereum:0x5287af72afbc152b09b3bf20af3693157db9e425"><img src="https://img.shields.io/badge/Ethereum-627EEA?style=plastic&logo=ethereum&logoColor=white" alt="Ethereum"></a> `0x5287af72afbc152b09b3bf20af3693157db9e425`
- <a href="solana:HYZjfEx8NbEMJX1vL1GmGj39zA6TgMsHm5KCHWSZxF4j"><img src="https://img.shields.io/badge/Solana-9945FF?style=plastic&logo=solana&logoColor=white" alt="Solana"></a> `HYZjfEx8NbEMJX1vL1GmGj39zA6TgMsHm5KCHWSZxF4j`
- <a href="monero:86zv6vTDuG35sdBzBpwVAsD71hbt2gjH14qiesyrSsMkUAWHQkPZyY9TreeQ5dXRuP57yitP4Yn13SQEcMK4MhtwFzPoRR1"><img src="https://img.shields.io/badge/Monero-FF6600?style=plastic&logo=monero&logoColor=white" alt="Monero"></a> `86zv6vTDuG35sdBzBpwVAsD71hbt2gjH14qiesyrSsMkUAWHQkPZyY9TreeQ5dXRuP57yitP4Yn13SQEcMK4MhtwFzPoRR1`

---

## Contact & Discussion

- **GitHub Issues:** Bug reports and feature requests
- **GitHub Discussions:** Coming soon for community Q&A
- **Email:** pub.inbox@proton.me

---

## License

Licensed under:

- MIT license ([LICENSE-MIT](https://github.com/moscovium-mc/arachNIDS-NG/blob/main/LICENSE))

---

## Acknowledgments

This project stands on the shoulders of giants:

- **arachNIDS** for the original arachNIDS vision
- The **Snort Project** for pioneering open-source IDS
- The **Suricata Community** for advancing the field
- Early network security researchers who built the foundations

Built with respect for the past and optimism for the future of defensive security.

---

<div align="center">

**Star this repository to follow development**

*Carrying forward 25+ years of IDS innovation*

</div>
