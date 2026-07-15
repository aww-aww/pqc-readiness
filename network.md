This is a first pass that was AI generated (via a combination of Gemini and Claude). It has not been human vetted in a meaningful way yet.

### Cisco

| Equipment Name | Version | Status | Supported Algorithms | Notes / Trackers |
|---|---|---|---|---|
| Catalyst 9500 Series Switches | IOS-XE 26.1.1+ | 🟡 In Progress | ML-KEM, LMS, ML-DSA-87 | Supports PQC MACsec and secure boot verification. |
| Catalyst 9600 Series Switches | IOS-XE 26.1.1+ | 🟡 In Progress | ML-KEM, LMS, ML-DSA-87 | PQC MACsec support for Layer 2 LAN edge protection. |
| Catalyst 9400 Series Switches | IOS-XE 26.1.1+ | 🟡 In Progress | ML-KEM, LMS, ML-DSA-87 | Hardware-rooted chain of trust via Trust Anchor module (TAm). |
| Catalyst 9300 Series Switches | IOS-XE 26.1.1+ | 🟡 In Progress | ML-KEM, LMS, ML-DSA-87 | Implements quantum-resistant signature algorithms. |
| Catalyst 9200 Series Switches | IOS-XE | 🔴 Not Started | N/A | Roadmap evaluation pending for lower-end access models. |
| 8100 Series Secure Router | IOS-XR / 26.1.1+ | 🟢 Ready | ML-KEM, Hash-Based Sigs (HBS) | Provides quantum-safe secure boot (HBS precursor to LMS). |
| 8200 Series Secure Router | IOS-XR / 26.1.1+ | 🟢 Ready | ML-KEM, ML-DSA-87, LMS | IKEv2/IPsec VPN key exchange using ML-KEM (FIPS 203). |
| 8800 Series Secure Router | IOS-XR / 26.1.1+ | 🟢 Ready | ML-KEM, ML-DSA-87, LMS | Silicon One powered. Full-stack PQC architecture. |
| Secure Firewall 4215 | FTD / FXOS | 🟢 Ready | Hash-Based Sigs (HBS) | Secure boot verified via quantum-resistant algorithms. |
| Secure Firewall 7100 Series | FTD / FXOS | 🟡 In Progress | Hybrid PQC | Integration for PQC VPN and telemetry in progress. |
| Secure Firewall 3100 Series | FTD / FXOS | 🟡 In Progress | Hybrid PQC | Next-gen cryptographic transition planned. |

### Juniper

| Equipment Name | Version | Status | Supported Algorithms | Notes / Trackers |
|---|---|---|---|---|
| PTX10000 Series Routers | Junos OS EVO 25.4+ | 🟢 Ready | sntrup761, X25519, ML-DSA-87 | Shor-resistant SSH key exchange; off-box PQC image verification. |
| PTX10008 Router | Junos OS EVO 25.4+ | 🟢 Ready | sntrup761, ML-DSA-87 | CNSA 2.0 compliant digital signatures for OS integrity. |
| ACX7000 Series Routers | Junos OS EVO 25.4+ | 🟢 Ready | sntrup761, X25519, ML-DSA-87 | Quantum Buffer in SSH limits FFC vulnerability. |
| ACX5000 Series Routers | Junos OS EVO 25.4+ | 🟢 Ready | sntrup761, X25519 | Hybrid classical/post-quantum SSH support. |
| QFX10000 Series Switches | Junos OS / EVO | 🟢 Ready | sntrup761, ML-DSA-87 | MACsec and SSH PQC implementations enabled. |
| QFX5200 Series Switches | Junos OS / EVO | 🟢 Ready | sntrup761, ML-DSA-87 | PQC-signed Junos OS Evolved software images. |
| QFX5100 Series Switches | Junos OS / EVO | 🟡 In Progress | sntrup761 | Partial rollout depending on specific image capabilities. |
| MX960 Universal Router | Junos OS | 🟡 In Progress | QKD API, Hybrid PQC | Integrates with Quantum Key Distribution (QKD) via ETSI GS QKD 014. |
| MX10003 Universal Router | Junos OS | 🟡 In Progress | QKD API, Hybrid PQC | IPsec VPN/MACsec integration with QKD and EvolutionQ. |
| SRX5000 Series Firewalls | Junos OS | 🟡 In Progress | Post-Quantum PPK | IKEv2 RFC 8784 post-quantum preshared keys (PPKs) support. |
| SRX4000 Series Firewalls | Junos OS | 🟡 In Progress | Post-Quantum PPK | Post-quantum VPN security scaling. |
| SRX1500 Firewall | Junos OS | 🟡 In Progress | Post-Quantum PPK | Out-of-band key mechanisms and PPK mixing. |

### Palo Alto Networks

| Equipment Name | Version | Status | Supported Algorithms | Notes / Trackers |
|---|---|---|---|---|
| PA-5500 Series NGFW | PAN-OS 12.1 Orion | 🟢 Ready | ML-KEM, PQC KEMs | Built to decrypt and inspect PQC-encrypted TLS traffic. |
| PA-5400 Series NGFW | PAN-OS 12.1 Orion | 🟢 Ready | ML-KEM, PQC KEMs | Cipher translation feature upgrades legacy app sessions. |
| PA-3400 Series NGFW | PAN-OS 12.1 Orion | 🟢 Ready | ML-KEM, PQC KEMs | Quantum Readine
