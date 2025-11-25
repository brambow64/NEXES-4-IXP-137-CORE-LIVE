# Security Policy — NEXUS - IXP-137 CORE

This document defines the security policy for the **IXP-137 CORE** repository.
Its purpose is to prevent misuse, clarify boundaries, and ensure that the
project's experimental nature is respected at all times.


## 🧪 1. Experimental Status (Critical Notice)

The IXP-137 CORE is **experimental software**.

It is **not**:

- a safety-critical system  
- an emergency-warning system  
- a real-time hazard detection system  
- an operational monitoring service  

Because of this, **security vulnerabilities cannot be treated in the same way as
in production software**.

All reports must acknowledge — and never contradict — the  
**IXP-137 Experimental Research License (ERL-1.0)**.


## ❗ 2. What *Is* Considered a Security Issue

You may submit a security report **only if** it concerns:

- Unauthorized code execution paths  
- Remote code execution risks introduced by dependencies  
- Manipulation of log output leading to system instability  
- Malicious payload vectors within data ingestion  
- Abuse avenues that may compromise contributors’ machines  
- Leakage of personal information if logs were misconfigured  
- Any vulnerability that allows *technical* misuse of the software

Reports must be submitted **privately via GitHub Security Advisory**.


## 🚫 3. What is *Not* a Security Issue

To avoid incorrect or non-actionable reports, the following are **not** valid
security concerns:

- Seismic prediction accuracy  
- Algorithmic uncertainties  
- False positives or false negatives  
- Any form of misinterpretation of hazard output  
- Theoretical disagreements about physics or forecasting  
- Incorrect assumptions about tectonic or volcanological behavior  
- Interpretation of model output as "dangerous" or "misleading"  
- Claims that the system “could warn people incorrectly”  
- Real-world impact of predictions (the system does not serve that purpose)

These items fall under **scientific discussion**, not security.


## 📢 4. Reporting a Valid Security Issue

If you believe you have found a valid technical vulnerability:

1. **Do not open a public GitHub issue**  
2. Go to: **GitHub → Security → Report a Vulnerability**  
3. Provide:  
   - Description  
   - Steps to reproduce  
   - Impact  
   - Suggested fix  
   - Environment details  

The maintainers will respond as soon as possible.


## 🛡️ 5. Supported Versions

| Version | Status | Notes |
|--------|--------|-------|
| `main` | ✔️ Supported | All fixes land here |
| Older/archived branches | ❌ Not supported | No backports or patches |

Only the **main** branch receives security-related changes.


## 🧩 6. Dependencies & Third-Party Code

If the security issue lies in a dependency:

- Please include version numbers  
- Include traceback or PoC (Proof of Concept)  
- Do *not* contact dependency authors through this repository  
- The maintainers will forward or address upstream if necessary


## 🧬 7. Final Disclaimer

Reporting security issues does **not** imply that the IXP-137 CORE is an
operational system requiring protection.

This policy exists solely to:

- keep contributors safe  
- prevent code abuse  
- prevent misunderstanding of the project's purpose  
- comply with GitHub’s security guidelines

Thank you for helping keep the project secure.
