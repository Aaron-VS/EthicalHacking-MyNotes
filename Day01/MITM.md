# 🕵️ Man-in-the-Middle (MITM) Attacks

Welcome to the **Man-in-the-Middle (MITM) Attacks** repository. This repo provides an educational overview of how MITM attacks work, common techniques used by attackers, and how to defend against them.

> ⚠️ **Disclaimer:** This content is for **educational purposes only**. Do not use any tools or techniques described here on networks or systems you do not own or have explicit permission to test. Unauthorized activity is illegal and unethical.

---

## 📖 What is a MITM Attack?

A **Man-in-the-Middle (MITM)** attack is a type of cyberattack where an attacker secretly intercepts and possibly alters communications between two parties who believe they are communicating directly.

### 🧷 Typical Flow:
1. Victim A sends data to Victim B.
2. Attacker intercepts the data in transit.
3. Attacker can:
   - Eavesdrop (passive)
   - Modify or inject data (active)

---

## ⚙️ Types of MITM Attacks

| Type | Description |
|------|-------------|
| **ARP Spoofing** | Maps attacker’s MAC to the IP of the gateway/router. |
| **DNS Spoofing** | Redirects traffic to fake/malicious domains. |
| **HTTPS Downgrade (SSL Strip)** | Forces a downgrade from HTTPS to HTTP. |
| **Wi-Fi Eavesdropping** | Sets up rogue Wi-Fi access points. |
| **Session Hijacking** | Steals session cookies to impersonate a user. |
| **Email Hijacking** | Intercepts email traffic to steal login credentials. |

---

## 🎯 Goals of MITM Attacks

- Steal login credentials
- Intercept credit card numbers
- Inject malicious content (e.g., phishing links, malware)
- Hijack user sessions and impersonate victims

---

## 🧰 Common Tools Used

| Tool | Purpose |
|------|---------|
| **Ettercap** | ARP spoofing, sniffing, and manipulation |
| **Wireshark** | Packet capturing and analysis |
| **mitmproxy** | Intercept and modify HTTP/S traffic |
| **Bettercap** | Full-featured MITM framework |
| **dsniff** | Password sniffing, ARP spoofing tools |

---

## 🛡️ How to Prevent MITM Attacks

| Method | Description |
|--------|-------------|
| **Use HTTPS** | Always prefer websites with SSL/TLS encryption. |
| **Use VPNs** | Encrypts traffic on untrusted networks. |
| **Verify SSL Certificates** | Check for valid digital certificates. |
| **Avoid Public Wi-Fi** | Or use a VPN when necessary. |
| **Enable MFA/2FA** | Even if credentials are stolen, accounts remain protected. |
| **Use Strong Network Security** | Segmentation, monitoring, and endpoint protection. |

---

## 📌 Real-World Example

> In 2011, attackers used a fake SSL certificate (from a compromised CA, DigiNotar) to intercept Gmail traffic in Iran. This MITM attack exposed communications of thousands of users.

---

## 🧠 Summary

| Aspect | Details |
|--------|---------|
| **Threat Type** | Interception / Impersonation |
| **Target** | User-to-user or user-to-server communication |
| **Risk Level** | High |
| **Impact** | Data theft, account compromise, malware injection |
| **Prevention** | Encryption, VPNs, MFA, certificate validation |

---

## 🧪 For Learning and Testing (Legally)

Try simulating MITM attacks in a **virtual lab** environment only:
- Set up using **VirtualBox** or **VMware**
- Use test tools like **Kali Linux**, **mitmproxy**, **Bettercap**
- Never attack real-world networks without permission

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

> 💡 Want diagrams, example scripts, or lab setups? Open an issue or submit a PR!

