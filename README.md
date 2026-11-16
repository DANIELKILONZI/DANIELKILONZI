```
┌──────────────────────────────────────────────────────────────────────────────┐
│  DANIEL KILONZI KIMEU                                                        │
│  Systems Architect • Embedded Security • Frontier Infrastructure             │
│  Nairobi, Kenya (EAT / UTC+3) • pulsewavelabskenya@gmail.com                 │
└──────────────────────────────────────────────────────────────────────────────┘
```

I build systems at the physical edges — where low-level silicon registers, hostile networks, and emerging-market economics collide.

Most modern software is built on comfortable Western assumptions: infinite cloud compute, clean 240V mains power, fast fiber internet, and trusted operating environments. I engineer for the opposite reality: rolling power blackouts, off-grid intermittent connectivity, constrained ARM silicon, and adversarial physical conditions.

Founder @ **Silicon Oath** (Pulsewave Labs) — engineering an air-gapped, phone-to-phone hardware diagnostic cyberdeck running inside rootless Android POSIX. It replaces $600 desktop repair rigs with a $50 smartphone, executing entirely in sealed volatile RAM with offline asymmetric cryptographic provisioning.

---

### Core Engineering Focus

- **Low-Level Systems & Firmware**: C99, POSIX shell, Linux kernel anonymous memory sealing (`memfd_create`), AOT-compiled ELF binaries, Android HAL/sysfs, and ARM64 assembly.
- **Applied Cryptography**: Offline Ed25519 token delegation, monotonic boot-anchored clocks, and tamper-evident SHA-256 hash-chained ledgers.
- **Resilient Protocol Design**: Asynchronous store-and-forward networks, binary wire serialization, sneakernet synchronization, and zero-dependency peer-to-peer transport.
- **Frontier Fintech & Forensics**: Real-time Safaricom M-PESA Daraja micro-metering, transaction graph forensics, and asset financing collateral lien detection under Kenya Penal Code §322.

---

### Flagship Venture

#### **Silicon Oath** `[Proprietary Fleet Infrastructure • Private Deployment]`
*The Sovereign Mobile Diagnostic Cyberdeck & Cryptographic Repair Substrate*

Across emerging markets, 500,000+ independent technicians keep hundreds of millions of smartphones alive, but rely on expensive, proprietary desktop equipment and cracked foreign software that frequently compromises customer privacy and wipes user data.

Silicon Oath replaces tethered desktop repair setups with an air-gapped mobile diagnostic cyberdeck running directly on smartphones technicians already own:
- **Zero Forensic Disk Footprint**: Diagnostic engines unpack and execute entirely within volatile kernel memory sealed with `F_SEAL_GROW | F_SEAL_WRITE | F_SEAL_SEAL`. Customer photos, private messages, and banking tokens leave zero footprint on persistent storage.
- **Air-Gapped Delegated Trust**: Hierarchical Ed25519 public-key infrastructure enables offline lease issuance, device quotas, and audit verification across disconnected field nodes without internet.
- **Fractional Micro-Metering**: Native integration with African mobile money rails (M-PESA), aligning operational costs with daily diagnostic volume via prepaid burn-on-run architecture.
- **Inviolable Invariants**: Programmatic enforcement of **0% Customer Data Loss** and **Samsung Knox 0x0 fuse preservation**.

---

### Selected Public Systems & Protocol Projects

- **[Mobile Money Fraud DNA System](https://github.com/DANIELKILONZI/Mobile-Money-Fraud-DNA-System)**  
  Heuristic anomaly detection and transaction graph forensics built specifically for high-velocity African mobile money networks (M-PESA, Airtel Money). Distinguishes synthetic fraud velocity from authentic informal market trading patterns without black-box ML.

- **[Offline-First Internet Layer](https://github.com/DANIELKILONZI/Offline-First-Internet-Layer)**  
  A zero-dependency store-and-forward transport protocol engineered for ultra-high-latency, intermittent cellular connections and off-grid African rural communities. Opportunistic sneakernet sync with cryptographically signed payloads.

- **[Human-Readable Binary Protocol](https://github.com/DANIELKILONZI/Human-Readable-Binary-Protocol)**  
  Deterministic network serialization engine. Combines the bit-level packing density of binary wire protocols with self-describing framing that can be inspected directly in plain text or zero-copy Wireshark dissectors.

- **[EMP-Hardened RF Spectrum Monitor](https://github.com/DANIELKILONZI/EMP-Hardened-RF-Spectrum-Monitor-for-Critical-Infra)**  
  Hardware-level radio frequency boundary telemetry and anomalous spectral shift detector designed to monitor critical telecommunication infrastructure under hostile electromagnetic interference.

- **[Protocol Virtual Machine](https://github.com/DANIELKILONZI/Protocol-Virtual-Machine)** & **[Living Network Stack](https://github.com/DANIELKILONZI/Living-Network-Stack)**  
  Sandboxed, deterministic bytecode execution engine for dynamic packet topology reconfiguration, declarative wire framing, and stateful protocol evaluation.

- **[Crucix](https://github.com/DANIELKILONZI/Crucix)** & **[Reality-Substrate-OS](https://github.com/DANIELKILONZI/Reality-Substrate-OS)**  
  Experimental runtime substrates exploring resilient execution boundaries, sandboxed state machines, and low-level kernel abstractions.

---

### System Architecture & Engineering Creed

```
[ Physical Handset ] ──(USB-C OTG)──> [ Volatile Memory Sandbox ]
                                             │
                                     (C99 memfd_create)
                                             │
                                             ▼
                                  { Knox 0x0 & Invariant Check }
                                    ├── Pass ──> [ Multi-Vector Silicon Triage ]
                                    └── Fail ──> [ Fail-Closed Quarantine ]
                                                       │
                                                       ▼
                                        [ Ed25519 Signed Audit Docket ]
                                        [ M-PESA Prepaid Fuel Burn ]
```

> *"The most dangerous assumption in software is that the happy path is the only path."*

- **Happy paths are cheap**: Anyone can write code that works when the API returns 200 OK, the battery is full, and the WiFi is 100 Mbps. Production systems are defined by how they fail when the cable is unplugged mid-write.
- **Zero forensic footprint**: If software doesn't need to write customer PII to persistent disk, it shouldn't. Anonymous volatile RAM execution isn't a feature; it is an architectural invariant.
- **Instruments before features**: If a subsystem can fail silently, it will. An audit log is the only honest artifact in a broken system.
- **Code deletion is progress**: The best commit is a negative diff that hardens the perimeter.

---

### Outside the Terminal

- **Chess**: Positional player. The endgame is the only honest part of the board.
- **Hardware**: Microcontrollers, custom circuits, logic analyzers, and Qualcomm Snapdragon test benches. Software is always more fun when it touches metal.
- **Nairobi (GMT+3)**: Midnight builder. Shipping systems while the rest of the world is asleep.
- **Focus OS**: Drum & bass when debugging, total silence when writing cryptographic logic.

---

### Contact & Collaboration

Open to conversations with systems engineers, founders, and teams tackling hard security, low-level Linux/POSIX, or distributed infrastructure problems.

- **Email**: [pulsewavelabskenya@gmail.com](mailto:pulsewavelabskenya@gmail.com)
- **LinkedIn**: [Daniel Kimeu](https://www.linkedin.com/in/daniel-kimeu-7274491b4)
- **GitHub**: [DANIELKILONZI](https://github.com/DANIELKILONZI)
- **PGP**: Available upon request
