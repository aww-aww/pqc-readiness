# PQC Readiness Tracker: Cryptography Libraries and Tools

This page tracks the state of Post-Quantum Cryptography (PQC) readiness for common cryptography libraries and tools.

These trackers are a crowdsourced effort; please contribute by updating the status of packages you maintain or use.

## Common Cryptography Packages

*** Seed data, not complete ***

| Package Name | Version| Status | Language | Supported Algorithms | Notes |
| :--- | :--- | :--- | :--- | :--- | :--- |
| Example Package | 1.0 | 🔴 Not Started | C, Go | ML-KEM,  ML-DSA, Other (LMS, SLH-DSA, Falcon) | Link to issue/PR |
| BoringSSL | [>=20250818](https://github.com/google/boringssl/releases/tag/0.20250818.0) | 🟢 Ready | C/C++ | ML-KEM, ML-DSA | https://commondatastorage.googleapis.com/chromium-boringssl-docs/mlkem.h.html |
| bssl-crypto | | Rust | ✓ | | | 
| Conscrypt| | Java | ✓ | | |
| Go crypto | [>=1.25.1](https://pkg.go.dev/crypto/mlkem@go1.25.1) | 🟢 Ready | Go | | https://github.com/golang/go/issues/64537 |
| OpenSSL | [>=3.5](https://openssl-library.org/post/2025-04-08-openssl-35-final-release/) | 🟢 Ready | C/C++ | | https://openssl.foundation/news/the-features-of-3-5-post-quantum-cryptography |


Status: 🟢 Ready / 🟡 In Progress / 🔴 Not Started

Readiness: ✅ / ⏳ / ❌

## Readiness Criteria
- **Inventory**: Does the package identify all non-PQC cryptographic dependencies?
- **Algorithm Support**: Does it support NIST-standardized PQC algorithms?
- **Agility**: Can the package switch between classical, hybrid, and PQC-only modes?

## How to Contribute
1. Fork this repo.
2. Update the table above with current information.
3. Submit a Pull Request with the tag `[PQC-Readiness]`.
