# PQC Readiness Tracking Template

This page tracks the state of Post-Quantum Cryptography (PQC) readiness for common packages and libraries. This is a crowdsourced effort; please contribute by updating the status of packages you maintain or use.

## Package Status Registry

| Package Name | Version | Status | Supported Algorithms | Notes / Trackers |
| :--- | :--- | :--- | :--- | :--- |
| [Example Package] | 1.0 | 🔴 Not Started | ML-KEM, ML-DSA | Link to issue/PR |
| | | | | |

Status:  🟢 Ready / 🟡 In Progress / 🔴 Not Started

## Readiness Criteria
- **Inventory**: Does the package identify all non-PQC cryptographic dependencies?
- **Algorithm Support**: Does it support NIST-standardized PQC algorithms?
- **Agility**: Can the package switch between classical, hybrid, and PQC-only modes?

## How to Contribute
1. Fork this repo.
2. Update the table above with current information.
3. Submit a Pull Request with the tag `[PQC-Readiness]`.
