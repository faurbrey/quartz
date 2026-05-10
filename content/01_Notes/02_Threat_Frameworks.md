# 🧩 02 Threat Frameworks

## ⛓️ Cyber Kill Chain (Lockheed Martin)
A linear model showing the stages an attacker must complete to succeed.
![[Kill_Chain.png]]

## 🛡️ MITRE ATT&CK® Framework
Moves focus from *what* we are protecting to *how* attackers actually operate.
- **Tactics:** The attacker's goal (e.g., [[03_Initial_Access_Vectors|Initial Access]]).
- **Techniques:** The method used (e.g., T1566 Phishing).

> [!DANGER] Case Study: Fake Captcha (2024)
> Attackers use **SEO Poisoning** to lure users to a fake CAPTCHA.
> 1. User clicks "I am not a robot."
> 2. Instructions tell user to press `Win + R` then `Ctrl + V`.
> 3. This pastes a malicious **PowerShell** command directly into the Windows Run box.
> 4. **Result:** Full system compromise via fileless malware.

## 🕵️ The Red vs. Blue Dynamic
- **Red Team:** Offensive security. They hack things before threat actors do to find weaknesses.
- **Blue Team:** Defensive security. They monitor traffic and implement firewalls.

---
[[START HERE|Return to Home]]