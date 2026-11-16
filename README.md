# Daniel Kilonzi
### Systems Architect • Embedded Security • Nairobi, Kenya

I build software at the physical edges — where low-level silicon, hostile networks, and real-world economics collide. 

Most modern software is built on comfortable assumptions: infinite cloud compute, clean 240V mains power, fast fiber internet, and trusted environments. I build for the opposite reality: intermittent power, zero connectivity, constrained ARM silicon, and adversarial physical conditions.

Founder @ **Silicon Oath** — building an air-gapped, phone-to-phone hardware diagnostic cyberdeck that runs inside rootless Android POSIX. It replaces $600 desktop repair rigs with a $50 smartphone, executing entirely in sealed volatile RAM with offline asymmetric cryptographic provisioning.

---

### Core Engineering Focus

- **Low-Level Systems**: C99, POSIX shell, Linux kernel memory sealing (`memfd_create`), AOT binaries, Android HAL/sysfs, ARM64.
- **Applied Cryptography**: Offline Ed25519 token delegation, monotonic boot-anchored clocks, tamper-evident hash-chained ledgers.
- **Resilient Protocols**: Asynchronous store-and-forward networks, binary wire serialization, zero-dependency peer-to-peer transport.
- **Frontier Fintech**: Real-time M-PESA micro-billing, fraud forensics, and asset financing lien detection.

---

### Selected Public Projects

#### [Mobile Money Fraud DNA System](https://github.com/DANIELKILONZI/Mobile-Money-Fraud-DNA-System)
Heuristic anomaly detection and transaction graph forensics built specifically for high-velocity African mobile money networks (M-PESA). Distinguishes synthetic fraud velocity from authentic informal market trading patterns without black-box ML.

#### [Offline-First Internet Layer](https://github.com/DANIELKILONZI/Offline-First-Internet-Layer)
A zero-dependency store-and-forward transport protocol engineered for ultra-high-latency, intermittent cellular connections and off-grid communities. Opportunistic sneakernet sync with cryptographically verified payloads.

#### [Human-Readable Binary Protocol](https://github.com/DANIELKILONZI/Human-Readable-Binary-Protocol)
Deterministic network serialization engine. Combines the bit-level packing density of binary wire protocols with self-describing framing that can be inspected directly in text or zero-copy Wireshark dissectors.

#### [EMP-Hardened RF Spectrum Monitor](https://github.com/DANIELKILONZI/EMP-Hardened-RF-Spectrum-Monitor-for-Critical-Infra)
Hardware-level radio frequency boundary telemetry and anomalous spectral shift detector designed to monitor critical telecommunication infrastructure under hostile interference.

#### [Living Network Stack](https://github.com/DANIELKILONZI/Living-Network-Stack) & [Protocol Virtual Machine](https://github.com/DANIELKILONZI/Protocol-Virtual-Machine)
Sandboxed, deterministic execution engine for custom wire protocols and stateful packet evaluation.

---

### How I Think About Software

> *"The most dangerous assumption in software is that the happy path is the only path."*

- **Happy paths are cheap**: Anyone can write code that works when the API returns 200 OK, the battery is full, and the WiFi is 100 Mbps. Production systems are defined by how they fail when the cable is unplugged mid-write.
- **Zero forensic footprint**: If software doesn't need to write customer PII to disk, it shouldn't. Anonymous volatile RAM execution isn't a feature; it's a moral and architectural invariant.
- **Instruments before features**: If a subsystem can fail silently, it will. An audit log is the only honest artifact in a broken system.
- **Code deletion is progress**: The best diff is a negative diff that hardens the perimeter.

---

### Outside the Terminal

- **Chess**: Positional player. The endgame is the only honest part of the board.
- **Hardware**: Microcontrollers, custom circuits, logic analyzers, and Qualcomm Snapdragon test benches. Software is more fun when it touches metal.
- **Nairobi (GMT+3)**: Midnight builder. Shipping systems while the rest of the world is asleep.
- **Focus**: Drum & bass for debugging, silence when writing cryptographic logic.

---

### Contact

- **Email**: [dnlkilonzi@gmail.com](mailto:dnlkilonzi@gmail.com)
- **LinkedIn**: [Daniel Kimeu](https://www.linkedin.com/in/daniel-kimeu-7274491b4)
- **GitHub**: [DANIELKILONZI](https://github.com/DANIELKILONZI)
