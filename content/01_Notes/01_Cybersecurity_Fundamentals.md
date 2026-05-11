# 🛡️ 01 Cyber security Fundamentals

## 🌟 Definition
**Cyber security** is the practice of protecting computer systems, networks, and sensitive data from theft, damage, or unauthorized access.

## 🏛️ The Three Pillars of the SOC
Security is not just software; it is a balance of three elements:
![[SOC_Pillars.png]]

> [!INFO] SOC Roles
> - **Tier 1:** Alert Analysts (Frontlines)
> - **Tier 2:** Incident Responders
> - **Tier 3:** Subject Matter Experts (Threat Hunters)

## ⚖️ The Risk Calculation
In security, we calculate the probability of a threat exploiting a vulnerability:
$$\text{Risk} = \text{Threat} \times \text{Vulnerability} \times \text{Impact}$$

## 📐 The CIA Triad Model
The foundational model for developing security policies.
![[CIA_Triad.png]]

### 1. Confidentiality
Ensuring data is accessed only by authorized entities.
- **Controls:** MFA, AES-256 Encryption, Principle of Least Privilege (PoLP).
- **Violations:** Phishing, MITM attacks, Data breaches.

### 2. Integrity
Guaranteeing that data is accurate and untampered with.
- **Controls:** Digital Signatures, Cryptographic Hashing (SHA-256).
- **Violations:** Unauthorized file changes, Spoofing.

### 3. Availability
Ensuring timely and reliable access for authorized users.
- **Controls:** Off-site backups, DDoS mitigation, RAID storage.
- **Violations:** Ransomware, Hardware failures.

---
[[index|Return to Home]]
