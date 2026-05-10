# 🪝 03 Initial Access Vectors

## 1. Phishing (T1566)
The "Human-Targeted" vector. Attackers trick users into revealing credentials.
- **Header Analysis:** We verify legitimacy using:
	- **SPF:** Verifies the sender's IP.
	- **DKIM:** Cryptographic signature for the message.
	- **DMARC:** Instructions for what to do if SPF/DKIM fails.
- **Tools:** [[VirusTotal]] (URL scanning), [[MXToolbox]] (Header analysis).

## 2. Exploit Public-Facing Application (T1190)
The "Infrastructure-Targeted" vector. No user interaction is required.
- **Discovery:** Attackers use [[Shodan]] to find open ports and unpatched software.
- **Notable CVEs:**
	- **Log4Shell:** Vulnerability in Java logging (CVE-2021-44228).
	- **ProxyLogon:** Critical Exchange Server exploit.

## 3. Valid Accounts (T1078)
The "Identity-Targeted" vector. Attackers bypass perimeters by simply logging in.
![[Attack_Funnel.png]]

> [!QUOTE] 
> "Attackers no longer break in; they log in." — 81% of breaches involve stolen or weak passwords.

### 🛡️ Defensive Strategy: Password Management
| Solution Type | Tool Examples | Advantage |
| --- | --- | --- |
| **Cloud-Based** | Bitwarden, 1Password | Cross-device sync, E2EE |
| **Local Storage** | KeePassXC, Gopass | Maximum privacy, Air-gapped |

---
[[START HERE|Return to Home]]