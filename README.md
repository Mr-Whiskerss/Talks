# Talks

A collection of technical security talks and presentations covering Active Directory attack techniques, anonymity, and offensive security concepts. All slide decks are free to use, share.

---

## Talks Index

### Active Directory Attack Series

A three-part series walking through Active Directory attacks from zero knowledge to full domain compromise. Designed for security professionals, red teamers, and those studying for certifications like OSCP, CEH, or preparing for adversary simulation engagements.

---

#### Active Directory 101 — Introduction & Fundamentals

> **File:** `Attacking Active Directory 101.pptx`

An introductory talk covering the foundational concepts of Active Directory from an attacker's perspective. Ideal for those new to AD security or wanting to build a solid baseline before moving into attack techniques.

**Topics covered:**
- What is Active Directory and why it matters
- Core AD components: domains, forests, trusts, OUs
- Key protocols: LDAP, Kerberos, SMB, NTLM
- Initial recon and enumeration concepts
- Setting the scene for common attack paths

📺 **YouTube Recording:** [Watch on YouTube](https://www.youtube.com/watch?v=Ey9sk6PB7gk)

---

#### Active Directory 102 — Common Attack Paths (Getting a Foothold)

> **File:** `Active Directory 102 Common Attack Paths (Getting a foothold).pptx`

A deep dive into real-world techniques used to gain an initial foothold within an Active Directory environment. Covers the methods most commonly seen on internal penetration tests and red team engagements.

**Topics covered:**
- LLMNR/NBT-NS poisoning with Responder
- NTLM relay attacks (ntlmrelayx)
- Password spraying and credential stuffing
- Kerberoasting and AS-REP Roasting
- SMB enumeration and null sessions
- Initial foothold techniques and common misconfigurations

---

#### Active Directory 103 — You Have Credentials, Now What?

> **File:** `AD103_v2_You_Have_Credentials.pptx`

The final instalment of the series, picking up from where you've obtained valid credentials and walking through post-credential attack techniques to escalate privileges and achieve domain dominance.

**Topics covered:**
- BloodHound/SharpHound for attack path enumeration
- Pass-the-Hash and Pass-the-Ticket
- Kerberoasting at scale
- DCSync and NTDS.dit extraction
- ADCS abuse (ESC misconfigurations)
- Golden & Silver Ticket attacks
- Lateral movement and persistence techniques

---

### 🧅 TOR — Anonymity, Onion Routing & Operational Security

> **File:** `Powerpoint_TOR.pptx`

A technical talk on the Tor network — how it works under the hood, its use cases in security research and OSINT, and its limitations from an operational security standpoint.

**Topics covered:**
- How onion routing works
- Tor circuit construction and relay types
- Operational security considerations
- Use cases in security research and threat intelligence
- Limitations and deanonymisation techniques

---

##  Usage

All decks are in `.pptx` format and can be opened with:

- Microsoft PowerPoint
- LibreOffice Impress (free)
- Google Slides (via import)

Feel free to use these slides for your own talks, training sessions, or self-study. Attribution is appreciated but not required.

---

##  Disclaimer

All content in this repository is intended **strictly for educational purposes** and use within authorised security engagements. The techniques discussed are shared to promote defensive awareness and to support the training of ethical security professionals.

**Do not use these techniques against systems you do not own or have explicit written permission to test.**

---

## Licence

This repository is licensed under the [GNU General Public Licence v3.0](LICENSE). You are free to use, modify, and distribute the contents as long as you maintain the same licence terms.

---

## 🔗 Links

- 📺 [AD 101 — YouTube Talk](https://www.youtube.com/watch?v=Ey9sk6PB7gk)
- 🐙 [GitHub Profile](https://github.com/Mr-Whiskerss)
