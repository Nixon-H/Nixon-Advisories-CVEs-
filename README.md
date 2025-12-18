# 🛡️ Nixon Advisories

### Security Research & Vulnerability Disclosures

A centralized archive of Security Advisories, CVEs, and Proof-of-Concepts (PoCs) for security vulnerabilities discovered by **Aditya Singh (Nixon-H)**.

This repository serves as a permanent record of identified vulnerabilities. Findings are categorized by their remediation status (Patched vs. Unpatched) to assist security teams in prioritization.

---

## ⚠️ Disclosure Policy & Disclaimer
The information provided here is for **educational purposes and security research reference only**.
* **Patched:** Vulnerabilities where the vendor has released a fix.
* **Unpatched:** Vulnerabilities currently without a known fix or in the grace period.

The author is not responsible for any misuse of the information provided herein.

---

## 🟢 Patched Vulnerabilities (Resolved)
*Vendor fixes are available. These are archived for historical reference and analysis.*

| CVE ID | Severity | Vendor / Product | Vulnerability Type | PoC Link |
| :--- | :--- | :--- | :--- | :--- |
| **[CVE-2025-68434](./Patched/CVE-2025-68434)** | 🔴 High | OpenSourcePOS | CSRF (Admin Account Takeover) | [View PoC](./Patched/CVE-2025-68434) |
| **[CVE-2025-68147](./Patched-CVE/CVE-2025-68147)** | 🟠 Medium | OpenSourcePOS | Stored Cross-Site Scripting (XSS) | [View PoC](./Patched-CVE/CVE-2025-68147) |

---

## 🔴 Unpatched Vulnerabilities (Active Threats)
*These vulnerabilities may not yet have a vendor fix available. Proceed with caution.*

| CVE ID | Severity | Vendor / Product | Vulnerability Type | PoC Link |
| :--- | :--- | :--- | :--- | :--- |
| **[CVE-2025-XXXX](./Unpatched/CVE-2025-XXXX)** | 🟣 Critical | VendorName | XXXXXXXXXXX| [View PoC](./Unpatched/CVE-2025-XXXX) |


---

## 📊 Severity Legend
| Icon | Level | CVSS Range |
| :---: | :--- | :--- |
| 🟣 | **Critical** | 9.0 - 10.0 |
| 🔴 | **High** | 7.0 - 8.9 |
| 🟠 | **Medium** | 4.0 - 6.9 |
| 🔵 | **Low** | 0.1 - 3.9 |

---

## 🔗 Contact
* **Researcher:** Aditya Singh
* **Handle:** [Nixon-H](https://github.com/Nixon-H)
* **Email:** Nixon-HByte@proton.me
