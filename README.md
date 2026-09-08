# 5h4d0wn1k — Cybersecurity Portfolio Index

Index and single-entry-point for the **146-repo** offensive & defensive security portfolio. Every repo is an independent, MIT-licensed, authorized-use-only tool with a working engine, an offline demo, and its own unit tests.

> **IMPORTANT: Read before use.** All software in this portfolio is for **authorized security education and testing only** — your own networks, systems, and hardware, or systems you have explicit written permission to assess. Unauthorized access attempts may violate the Computer Fraud and Abuse Act (18 U.S.C. §1030) and local law. Use responsibly. No warranty is provided; the authors assume no liability for misuse.

## Portfolio Metrics

| Metric | Value |
|---|---|
| Repositories | **146** |
| Security domains | **16** |
| Automated unit tests | **2135** |
| Python/firmware source files | **559** |
| License | MIT (all repos) |
| Legal disclaimer | All READMEs |
| Hardware projects (Arduino/ESP32) | 22 |

## Repository Index

Each entry below is a git submodule. `git clone --recursive` this repo to pull them all.


### AI / ML Security (8 repos)

| # | Repo | Tests | Files | Purpose |
|---|------|------:|------:|---------|
| 1 | [ai1-adversarial](https://github.com/5h4d0wn1k/ai1-adversarial) | 10 | 2 | AI1 — Adversarial ML Attacks |
| 2 | [ai2-model-poison](https://github.com/5h4d0wn1k/ai2-model-poison) | 8 | 2 | AI2 — Model Poisoning Tool |
| 3 | [ai3-data-exfil](https://github.com/5h4d0wn1k/ai3-data-exfil) | 10 | 2 | AI3 — Data Exfiltration via ML |
| 4 | [ai4-nn-backdoor](https://github.com/5h4d0wn1k/ai4-nn-backdoor) | 6 | 2 | AI4 — Neural Network Backdoor |
| 5 | [ai5-model-extract](https://github.com/5h4d0wn1k/ai5-model-extract) | 8 | 2 | AI5 — Model Extraction Tool |
| 6 | [ai6-fl-attack](https://github.com/5h4d0wn1k/ai6-fl-attack) | 7 | 2 | AI6 — Federated Learning Attack |
| 7 | [ai7-model-robustness](https://github.com/5h4d0wn1k/ai7-model-robustness) | 9 | 2 | AI7 — Model Robustness Auditor |
| 8 | [ai8-ai-code-audit](https://github.com/5h4d0wn1k/ai8-ai-code-audit) | 10 | 3 | AI8 — AI Code Audit |

### Cryptography & Protocol Attacks (8 repos)

| # | Repo | Tests | Files | Purpose |
|---|------|------:|------:|---------|
| 1 | [c1-hash-crack](https://github.com/5h4d0wn1k/c1-hash-crack) | 19 | 4 | C1 — Hash Cracker |
| 2 | [c2-rsa-attack](https://github.com/5h4d0wn1k/c2-rsa-attack) | 18 | 4 | C2 — RSA Common-Attack Suite |
| 3 | [c3-aes-attacks](https://github.com/5h4d0wn1k/c3-aes-attacks) | 12 | 4 | C3 — AES Oracle Attacks |
| 4 | [c4-cipher-challenges](https://github.com/5h4d0wn1k/c4-cipher-challenges) | 24 | 2 | C4 — Custom Cipher Challenges |
| 5 | [c5-blockchain](https://github.com/5h4d0wn1k/c5-blockchain) | 26 | 2 | C5 — Blockchain Analyzer |
| 6 | [c6-pass-hash](https://github.com/5h4d0wn1k/c6-pass-hash) | 30 | 2 | C6 — Password Hash Tool |
| 7 | [c7-wire-proto](https://github.com/5h4d0wn1k/c7-wire-proto) | 27 | 2 | C7 — Wire Protocol Analyzer |
| 8 | [c8-dh-demo](https://github.com/5h4d0wn1k/c8-dh-demo) | 18 | 2 | C8 — Diffie-Hellman Demo |

### Cloud & Container Security (8 repos)

| # | Repo | Tests | Files | Purpose |
|---|------|------:|------:|---------|
| 1 | [cl1-aws-s3](https://github.com/5h4d0wn1k/cl1-aws-s3) | 12 | 2 | CL1 — AWS S3 Bucket Scanner |
| 2 | [cl2-gcp-bucket](https://github.com/5h4d0wn1k/cl2-gcp-bucket) | 9 | 2 | CL2 — GCP Bucket Scanner |
| 3 | [cl3-docker-leak](https://github.com/5h4d0wn1k/cl3-docker-leak) | 16 | 2 | CL3 — Docker Secret Leaker |
| 4 | [cl4-k8s-secrets](https://github.com/5h4d0wn1k/cl4-k8s-secrets) | 17 | 2 | CL4 — Kubernetes Secret Scanner |
| 5 | [cl5-terraform-audit](https://github.com/5h4d0wn1k/cl5-terraform-audit) | 13 | 2 | CL5 — Terraform Plan Analyzer |
| 6 | [cl6-azure-vault](https://github.com/5h4d0wn1k/cl6-azure-vault) | 12 | 2 | CL6 — Azure Key Vault Scanner |
| 7 | [cl7-cloud-forensics](https://github.com/5h4d0wn1k/cl7-cloud-forensics) | 9 | 2 | CL7 — Cloud Forensics Toolkit |
| 8 | [cl8-cspm](https://github.com/5h4d0wn1k/cl8-cspm) | 8 | 2 | CL8 — Multi-Cloud CSPM Posture Auditor |

### Digital Forensics & Incident Response (8 repos)

| # | Repo | Tests | Files | Purpose |
|---|------|------:|------:|---------|
| 1 | [d1-memory-forensics](https://github.com/5h4d0wn1k/d1-memory-forensics) | 17 | 6 | D1 — Memory Forensics Toolkit |
| 2 | [d2-disk-analyzer](https://github.com/5h4d0wn1k/d2-disk-analyzer) | 18 | 6 | D2 — Disk Image Analyzer |
| 3 | [d3-log-analyzer](https://github.com/5h4d0wn1k/d3-log-analyzer) | 16 | 5 | D3 — Log Analyzer |
| 4 | [d4-net-forensics](https://github.com/5h4d0wn1k/d4-net-forensics) | 18 | 6 | D4 — Network Forensics Suite |
| 5 | [d5-registry-analyze](https://github.com/5h4d0wn1k/d5-registry-analyze) | 15 | 5 | D5 — Registry Analyzer |
| 6 | [d6-browser-forensics](https://github.com/5h4d0wn1k/d6-browser-forensics) | 13 | 5 | D6 — Browser Forensics |
| 7 | [d7-email-header](https://github.com/5h4d0wn1k/d7-email-header) | 16 | 4 | D7 — Email Header Analyzer |
| 8 | [d8-timeline-gen](https://github.com/5h4d0wn1k/d8-timeline-gen) | 17 | 4 | D8 — Timeline Generator |

### Frontier / 2026 Tooling (10 repos)

| # | Repo | Tests | Files | Purpose |
|---|------|------:|------:|---------|
| 1 | [f1-agentic-redteam](https://github.com/5h4d0wn1k/f1-agentic-redteam) | 42 | 26 | F1 — Agentic Red-Team Campaign Orchestrator |
| 2 | [f2-nids-robustness](https://github.com/5h4d0wn1k/f2-nids-robustness) | 16 | 3 | F2 — NIDS Adversarial Robustness (protocol-evasion corpus) |
| 3 | [f3-mcp-honeypot](https://github.com/5h4d0wn1k/f3-mcp-honeypot) | 12 | 3 | F3 — MCP (Model Context Protocol) Honeypot |
| 4 | [f4-multichannel-detector](https://github.com/5h4d0wn1k/f4-multichannel-detector) | 12 | 3 | F4 — Multichannel Threat Detector (web + net + host) |
| 5 | [f5-pq-scanner](https://github.com/5h4d0wn1k/f5-pq-scanner) | 15 | 3 | F5 — Post-Quantum Crypto Scanner |
| 6 | [f6-firmware-audit](https://github.com/5h4d0wn1k/f6-firmware-audit) | 18 | 3 | F6 — Firmware / Image Audit |
| 7 | [f7-edr-auditor](https://github.com/5h4d0wn1k/f7-edr-auditor) | 99 | 31 | F7 — EDR Auditor (endpoint hardening auditor, blue-team) |
| 8 | [f8-ztr-sandbox](https://github.com/5h4d0wn1k/f8-ztr-sandbox) | 10 | 3 | F8 — Zero-Trust Readiness Assessment Engine |
| 9 | [f9-supply-chain-gate](https://github.com/5h4d0wn1k/f9-supply-chain-gate) | 29 | 3 | F9 — Supply-Chain Integrity Gate |
| 10 | [f10-deception-grid](https://github.com/5h4d0wn1k/f10-deception-grid) | 25 | 3 | F10 — Deception Grid (decoy orchestration planner) |

### Hardware & Embedded (RF / BLE / SoC) (15 repos)

| # | Repo | Tests | Files | Purpose |
|---|------|------:|------:|---------|
| 1 | [h1-deauth-oled](https://github.com/5h4d0wn1k/h1-deauth-oled) | 3 | 4 | H1 — Deauth Detector |
| 2 | [h2-ble-tracker](https://github.com/5h4d0wn1k/h2-ble-tracker) | 1 | 4 | H2 — BLE Device Tracker |
| 3 | [h3-zigbee-sniffer](https://github.com/5h4d0wn1k/h3-zigbee-sniffer) | 3 | 4 | H3 — Zigbee/Thread Packet Sniffer |
| 4 | [h4-mousejack](https://github.com/5h4d0wn1k/h4-mousejack) | 3 | 4 | H4 — nRF24 Protocol Hacker (MouseJack) |
| 5 | [h5-433-replay](https://github.com/5h4d0wn1k/h5-433-replay) | 3 | 4 | H5 — 433 MHz Replay Attack Tool |
| 6 | [h6-spectrum](https://github.com/5h4d0wn1k/h6-spectrum) | 3 | 4 | H6 — Spectrum Analyzer |
| 7 | [h7-evil-twin-ap](https://github.com/5h4d0wn1k/h7-evil-twin-ap) | 3 | 4 | H7 — Evil Twin AP |
| 8 | [h8-rfid-spoofer](https://github.com/5h4d0wn1k/h8-rfid-spoofer) | 3 | 4 | H8 — RFID/NFC Spoofer |
| 9 | [h9-ir-blaster](https://github.com/5h4d0wn1k/h9-ir-blaster) | 3 | 4 | H9 — IR Blaster + Replay |
| 10 | [h10-usb-hid](https://github.com/5h4d0wn1k/h10-usb-hid) | 4 | 4 | H10 — USB HID Emulator |
| 11 | [h11-gps-spoof](https://github.com/5h4d0wn1k/h11-gps-spoof) | 3 | 4 | H11 — GPS Spoofer |
| 12 | [h12-drone-ctrl](https://github.com/5h4d0wn1k/h12-drone-ctrl) | 3 | 4 | H12 — Drone Controller |
| 13 | [h13-wifi-jammer](https://github.com/5h4d0wn1k/h13-wifi-jammer) | 3 | 4 | H13 — WiFi Jammer |
| 14 | [h14-lora-attack](https://github.com/5h4d0wn1k/h14-lora-attack) | 3 | 4 | H14 — LoRa Attack |
| 15 | [h15-sdr-capture](https://github.com/5h4d0wn1k/h15-sdr-capture) | 4 | 4 | H15 — SDR Signal Capture |

### IoT / SCADA / Embedded Protocols (8 repos)

| # | Repo | Tests | Files | Purpose |
|---|------|------:|------:|---------|
| 1 | [i1-firmware-extract](https://github.com/5h4d0wn1k/i1-firmware-extract) | 13 | 2 | I1 — IoT Firmware Extractor |
| 2 | [i2-mqtt-exploit](https://github.com/5h4d0wn1k/i2-mqtt-exploit) | 18 | 2 | I2 — MQTT Exploit Framework |
| 3 | [i3-zigbee-fuzz](https://github.com/5h4d0wn1k/i3-zigbee-fuzz) | 19 | 2 | I3 — Zigbee ZCL Attribute Fuzzer |
| 4 | [i4-upnp-exploit](https://github.com/5h4d0wn1k/i4-upnp-exploit) | 11 | 2 | I4 — UPnP Exploit Framework |
| 5 | [i5-modbus-scan](https://github.com/5h4d0wn1k/i5-modbus-scan) | 12 | 2 | I5 — Modbus Scanner |
| 6 | [i6-coap-replay](https://github.com/5h4d0wn1k/i6-coap-replay) | 20 | 2 | I6 — CoAP Replay Tool |
| 7 | [i7-can-bus](https://github.com/5h4d0wn1k/i7-can-bus) | 22 | 3 | I7 — CAN Bus Analyzer |
| 8 | [i8-ble-gatt](https://github.com/5h4d0wn1k/i8-ble-gatt) | 32 | 3 | I8 — BLE GATT Assessment |

### Malware Analysis & Reverse Engineering (11 repos)

| # | Repo | Tests | Files | Purpose |
|---|------|------:|------:|---------|
| 1 | [m1-static-analyzer](https://github.com/5h4d0wn1k/m1-static-analyzer) | 13 | 3 | M1 — Static Analyzer |
| 2 | [m2-dynamic-sandbox](https://github.com/5h4d0wn1k/m2-dynamic-sandbox) | 11 | 3 | M2 — Dynamic Analysis Sandbox |
| 3 | [m3-deobfuscator](https://github.com/5h4d0wn1k/m3-deobfuscator) | 11 | 4 | M3 — Deobfuscator |
| 4 | [m4-adb-exploit](https://github.com/5h4d0wn1k/m4-adb-exploit) | 14 | 2 | M4 — ADB Device Owner Audit Tool |
| 5 | [m4-yara-gen](https://github.com/5h4d0wn1k/m4-yara-gen) | 11 | 2 | M4 — YARA Rule Generator |
| 6 | [m5-frida-gen](https://github.com/5h4d0wn1k/m5-frida-gen) | 15 | 2 | M5 — Frida Hook Generator |
| 7 | [m6-backup-extract](https://github.com/5h4d0wn1k/m6-backup-extract) | 17 | 2 | MO6 — Android Backup Extractor |
| 8 | [m7-pe-analyzer](https://github.com/5h4d0wn1k/m7-pe-analyzer) | 21 | 2 | M7 — PE File Analyzer |
| 9 | [m8-elf-analyzer](https://github.com/5h4d0wn1k/m8-elf-analyzer) | 19 | 2 | M8 — ELF File Analyzer |
| 10 | [m9-shellcode-encoder](https://github.com/5h4d0wn1k/m9-shellcode-encoder) | 17 | 2 | M9 — Shellcode Encoder |
| 11 | [m10-bin-diff](https://github.com/5h4d0wn1k/m10-bin-diff) | 14 | 2 | M10 — Binary Diff Tool |

### Mobile Application Security (6 repos)

| # | Repo | Tests | Files | Purpose |
|---|------|------:|------:|---------|
| 1 | [mo1-apk-analyzer](https://github.com/5h4d0wn1k/mo1-apk-analyzer) | 16 | 2 | MO1 — Android APK Analyzer |
| 2 | [mo2-ios-binary](https://github.com/5h4d0wn1k/mo2-ios-binary) | 13 | 2 | MO2 — iOS Binary Analyzer |
| 3 | [mo3-cert-pin](https://github.com/5h4d0wn1k/mo3-cert-pin) | 9 | 2 | MO3 — Certificate Pinning Analyzer |
| 4 | [mo4-android-scan](https://github.com/5h4d0wn1k/mo4-android-scan) | 18 | 4 | MO4 — Android Vulnerability Scanner |
| 5 | [mo5-ios-assess](https://github.com/5h4d0wn1k/mo5-ios-assess) | 18 | 4 | MO5 — iOS Security Assessment |
| 6 | [mo6-mobile-malware](https://github.com/5h4d0wn1k/mo6-mobile-malware) | 15 | 4 | MO6 — Mobile Malware Analysis |

### Network Security (12 repos)

| # | Repo | Tests | Files | Purpose |
|---|------|------:|------:|---------|
| 1 | [n1-arp-guard](https://github.com/5h4d0wn1k/n1-arp-guard) | 7 | 2 | N1 — ARP Guard |
| 2 | [n2-dhcp-starve](https://github.com/5h4d0wn1k/n2-dhcp-starve) | 7 | 2 | N2 — DHCP Starvation (Lab / Portfolio) |
| 3 | [n3-dns-spoof](https://github.com/5h4d0wn1k/n3-dns-spoof) | 12 | 2 | N3 — DNS Spoof |
| 4 | [n4-port-knock](https://github.com/5h4d0wn1k/n4-port-knock) | 9 | 4 | N4 — Port Knocking Client/Server |
| 5 | [n5-vlan-hop](https://github.com/5h4d0wn1k/n5-vlan-hop) | 15 | 3 | N5 — VLAN Hopping (tag engine + gated live injection) |
| 6 | [n6-ip-spoof](https://github.com/5h4d0wn1k/n6-ip-spoof) | 15 | 2 | N6 — IP Spoof (offline checksum engine + gated live send) |
| 7 | [n7-honeypot-detect](https://github.com/5h4d0wn1k/n7-honeypot-detect) | 11 | 2 | N7 — Honeypot Detector |
| 8 | [n8-mac-changer](https://github.com/5h4d0wn1k/n8-mac-changer) | 16 | 2 | N8 — MAC Changer + Analyzer |
| 9 | [n9-evil-twin-scan](https://github.com/5h4d0wn1k/n9-evil-twin-scan) | 9 | 2 | N9 — WiFi Evil Twin Scanner |
| 10 | [n10-netmap-scan](https://github.com/5h4d0wn1k/n10-netmap-scan) | 12 | 3 | N10 — Netmap Scanner |
| 11 | [n11-proto-fuzz](https://github.com/5h4d0wn1k/n11-proto-fuzz) | 12 | 4 | N11 — Protocol Fuzzer |
| 12 | [n12-traffic-redirect](https://github.com/5h4d0wn1k/n12-traffic-redirect) | 17 | 3 | N12 — Traffic Redirector |

### Research Projects (3 repos)

| # | Repo | Tests | Files | Purpose |
|---|------|------:|------:|---------|
| 1 | [p2-esp-now-sok](https://github.com/5h4d0wn1k/p2-esp-now-sok) | 23 | 3 | P2 — ESP-NOW Security SoK — p2-esp-now-sok |
| 2 | [p4-xts-aes-sca](https://github.com/5h4d0wn1k/p4-xts-aes-sca) | 25 | 3 | P4 — XTS-AES Side-Channel CPA Engine |
| 3 | [p5-phytbed](https://github.com/5h4d0wn1k/p5-phytbed) | 27 | 3 | P5 — PHYTbed: multi-protocol PHY testbed orchestrator — p5-phytbed |

### Legacy Correlation (3 repos)

| # | Repo | Tests | Files | Purpose |
|---|------|------:|------:|---------|
| 1 | [r1-traffic-analyzer](https://github.com/5h4d0wn1k/r1-traffic-analyzer) | 23 | 2 | R1 — Network Traffic Analyzer v2 |
| 2 | [r2-malware-sigs](https://github.com/5h4d0wn1k/r2-malware-sigs) | 15 | 3 | R2 — Malware Signature Matcher |
| 3 | [r3-vuln-correlate](https://github.com/5h4d0wn1k/r3-vuln-correlate) | 15 | 3 | R3 — Vulnerability Correlator |

### Social Engineering / Human Factor (5 repos)

| # | Repo | Tests | Files | Purpose |
|---|------|------:|------:|---------|
| 1 | [se1-phishing](https://github.com/5h4d0wn1k/se1-phishing) | 9 | 3 | SE1 — Phishing Simulation Kit |
| 2 | [se2-osint](https://github.com/5h4d0wn1k/se2-osint) | 15 | 3 | SE2 — OSINT Lab Framework |
| 3 | [se3-pretext](https://github.com/5h4d0wn1k/se3-pretext) | 12 | 3 | SE3 — Pretext Lab Generator |
| 4 | [se4-vishing](https://github.com/5h4d0wn1k/se4-vishing) | 10 | 2 | SE4 — Vishing Lab Kit |
| 5 | [se5-physical-audit](https://github.com/5h4d0wn1k/se5-physical-audit) | 13 | 2 | SE5 — Physical Audit Lab Kit |

### Wireless / RF Software (17 repos)

| # | Repo | Tests | Files | Purpose |
|---|------|------:|------:|---------|
| 1 | [w1-deauth-eng](https://github.com/5h4d0wn1k/w1-deauth-eng) | 23 | 4 | W1 — Deauth/PMF Resilience Analysis & Deauth IDS `w1-deauth-eng` |
| 2 | [w1-wifi-scanner](https://github.com/5h4d0wn1k/w1-wifi-scanner) | 9 | 4 | W1 — WiFi Scanner + Signal Mapper |
| 3 | [w2-deauth-detect](https://github.com/5h4d0wn1k/w2-deauth-detect) | 9 | 4 | W2 — WiFi Deauth Detector |
| 4 | [w2-evil-twin](https://github.com/5h4d0wn1k/w2-evil-twin) | 13 | 4 | W2 — Evil-Twin Lab & Rogue-AP Detection `w2-evil-twin` |
| 5 | [w3-probe-audit](https://github.com/5h4d0wn1k/w3-probe-audit) | 10 | 4 | W3 — Probe-Request Privacy Audit (MAC Randomization) `w3-probe-audit` |
| 6 | [w3-probe-resp](https://github.com/5h4d0wn1k/w3-probe-resp) | 9 | 4 | W3 — WiFi Probe Responder |
| 7 | [w4-crack-pipeline](https://github.com/5h4d0wn1k/w4-crack-pipeline) | 30 | 14 | W4 — WPA/WPA2/PMKID Capture → Crack Pipeline |
| 8 | [w5-nrf-observer](https://github.com/5h4d0wn1k/w5-nrf-observer) | 15 | 4 | W5 — nRF24 Cross-Protocol Observer |
| 9 | [w6-beacon-analysis](https://github.com/5h4d0wn1k/w6-beacon-analysis) | 9 | 4 | W6 — Beacon Flood / SSID-Confusion Analysis |
| 10 | [w6-beacon-flood](https://github.com/5h4d0wn1k/w6-beacon-flood) | 11 | 4 | W6 — Beacon Flood |
| 11 | [w7-deauth-capture](https://github.com/5h4d0wn1k/w7-deauth-capture) | 10 | 4 | W7 — Deauth + Capture |
| 12 | [w7-wids-sensor](https://github.com/5h4d0wn1k/w7-wids-sensor) | 12 | 4 | W7 — Wireless IDS Sensor |
| 13 | [w8-covert-beacon](https://github.com/5h4d0wn1k/w8-covert-beacon) | 11 | 4 | W8 — Management-frame covert channel (exfil + detection) — w8-covert-beacon |
| 14 | [w8-evil-portal](https://github.com/5h4d0wn1k/w8-evil-portal) | 10 | 4 | W8 — Evil Portal + Captive |
| 15 | [w9-ble-spoofer](https://github.com/5h4d0wn1k/w9-ble-spoofer) | 13 | 4 | W9 — BLE Spoofer |
| 16 | [w9-resilient-tele](https://github.com/5h4d0wn1k/w9-resilient-tele) | 16 | 4 | W9 — Attack-resilient dual-band telemetry (HC-12 failover) — w9-resilient-tele |
| 17 | [w10-wpa3-survey](https://github.com/5h4d0wn1k/w10-wpa3-survey) | 11 | 4 | W10 — WPA3 Transition-Mode Neighborhood Survey `w10-wpa3-survey` |

### Web Application Security (12 repos)

| # | Repo | Tests | Files | Purpose |
|---|------|------:|------:|---------|
| 1 | [web1-sqli-auto](https://github.com/5h4d0wn1k/web1-sqli-auto) | 5 | 2 | WEB1 — SQL Injection Automation Tool |
| 2 | [web2-xss-scanner](https://github.com/5h4d0wn1k/web2-xss-scanner) | 4 | 2 | WEB2 — XSS Scanner + Payload Generator |
| 3 | [web3-csrf-tool](https://github.com/5h4d0wn1k/web3-csrf-tool) | 8 | 2 | WEB3 — CSRF Attack/Replay Tool |
| 4 | [web4-dirbrute](https://github.com/5h4d0wn1k/web4-dirbrute) | 5 | 2 | WEB4 — Directory Bruteforcer |
| 5 | [web5-subdomain](https://github.com/5h4d0wn1k/web5-subdomain) | 7 | 2 | WEB5 — Subdomain Scanner |
| 6 | [web6-http-smuggle](https://github.com/5h4d0wn1k/web6-http-smuggle) | 6 | 2 | WEB6 — HTTP Request Smuggler |
| 7 | [web7-xxe-inject](https://github.com/5h4d0wn1k/web7-xxe-inject) | 9 | 2 | WEB7 — XXE Injection Tool |
| 8 | [web8-ssti-scan](https://github.com/5h4d0wn1k/web8-ssti-scan) | 8 | 2 | WEB8 — SSTI Scanner |
| 9 | [web9-cors-scan](https://github.com/5h4d0wn1k/web9-cors-scan) | 9 | 2 | WEB9 — CORS Misconfiguration Scanner |
| 10 | [web10-webshell-gen](https://github.com/5h4d0wn1k/web10-webshell-gen) | 10 | 3 | WEB10 — Web Shell Generator (Lab) |
| 11 | [web11-cms-scan](https://github.com/5h4d0wn1k/web11-cms-scan) | 9 | 3 | WEB11 — CMS Vulnerability Scanner |
| 12 | [web12-browser-exploit](https://github.com/5h4d0wn1k/web12-browser-exploit) | 14 | 3 | WEB12 — Browser Exploit Framework (Lab) |

### Systems / Host Security (12 repos)

| # | Repo | Tests | Files | Purpose |
|---|------|------:|------:|---------|
| 1 | [x1-binrecon](https://github.com/5h4d0wn1k/x1-binrecon) | 37 | 2 | X1 — Binary Recon Tool — binrecon |
| 2 | [x2-exploit-ladder](https://github.com/5h4d0wn1k/x2-exploit-ladder) | 18 | 2 | X2 — Exploit Development Ladder — exploit_ladder |
| 3 | [x3-iot-fuzzer](https://github.com/5h4d0wn1k/x3-iot-fuzzer) | 17 | 2 | X3 — IoT Protocol Fuzzer — iot_fuzzer |
| 4 | [x4-hack-toolkit](https://github.com/5h4d0wn1k/x4-hack-toolkit) | 29 | 3 | X4 — Unified Hacker Toolkit — hack_toolkit |
| 5 | [x5-mitm-suite](https://github.com/5h4d0wn1k/x5-mitm-suite) | 34 | 22 | X5 — MITM and Spoofing Attack Suite |
| 6 | [x6-ml-siem](https://github.com/5h4d0wn1k/x6-ml-siem) | 20 | 19 | X6 — ML SIEM (Flow Baseline + Anomaly Scoring + Alert Feed) |
| 7 | [x7-kernel-monitor](https://github.com/5h4d0wn1k/x7-kernel-monitor) | 21 | 14 | X7 — Kernel/System Monitor |
| 8 | [x8-nids](https://github.com/5h4d0wn1k/x8-nids) | 33 | 15 | X8 — Network Intrusion Detection System |
| 9 | [x9-mitm-detectors](https://github.com/5h4d0wn1k/x9-mitm-detectors) | 26 | 3 | X9 — MITM and Spoofing Detectors |
| 10 | [x10-malware-classifier](https://github.com/5h4d0wn1k/x10-malware-classifier) | 28 | 4 | X10 — Malware Family Classification System |
| 11 | [x11-honeypot-stack](https://github.com/5h4d0wn1k/x11-honeypot-stack) | 16 | 4 | X11 — Honeypot Program (Full Stack) |
| 12 | [x12-ctf](https://github.com/5h4d0wn1k/x12-ctf) | 22 | 4 | X12 — CTF Toolkit + Challenge Authorship |

---

*Auto-generated by the portfolio index toolchain. 146 repos, 5h4d0wn1k.*
