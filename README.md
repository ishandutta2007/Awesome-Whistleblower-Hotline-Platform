# Awesome-Whistleblower-Hotline-Platform

# Top Whistleblower Hotline Platforms

A curated list of leading whistleblower hotline, ethics reporting, and anonymous case management platforms used by organizations for secure intake, investigation workflows, compliance (EU Whistleblower Directive, SOX, etc.), and speak-up programs.  
**Primary focus: open-source software.**

Commercial / hosted platforms are listed separately for completeness. Open-source alternatives and community tools are emphasized throughout.

---

## SaaS / Hosted Platforms

| Platform | Description | Key Focus |
|----------|-------------|-----------|
| **[NAVEX One](https://www.navex.com/)** (EthicsPoint) | Enterprise ethics and compliance platform with mature whistleblowing intake (EthicsPoint), case management, policy/training integration, and global compliance support. | Enterprise ethics & compliance hotline |
| **[WhistleB](https://www.whistleb.com/)** | Secure whistleblowing platform focused on anonymity, multilingual support, and case handling, popular in Europe. | Secure anonymous reporting |
| **[FaceUp](https://www.faceup.com/)** | Modern whistleblowing and employee feedback platform with portal, hotline options, anonymous chat, and case management. | User-friendly speak-up platform |
| **[People Intouch](https://www.peopleintouch.com/)** (SpeakUp) | Whistleblowing and speak-up solution with strong language coverage, privacy controls, and investigation support. | Multilingual speak-up & privacy |
| **[EthicsPoint](https://www.navex.com/)** (NAVEX) | Classic third-party hotline and incident management system widely used for anonymous reporting and compliance programs. | Traditional hotline + case mgmt |
| **[Convercent](https://www.onetrust.com/)** (OneTrust) | Ethics and compliance platform with whistleblowing intake, case workflows, policy management, and GRC integrations. | Ethics + GRC-integrated reporting |
| **[EQS Integrity Line](https://www.eqs.com/)** | Enterprise whistleblowing and integrity platform with hotline, portal, anonymous communication, and strong EU/enterprise focus. | Enterprise integrity & EU compliance |
| **[Safecall](https://www.safecall.co.uk/)** | Independent whistleblowing hotline and case management service with 24/7 intake and investigation support. | Independent hotline service |
| **[AllVoices](https://www.allvoices.co/)** | Modern anonymous reporting platform with two-way secure messaging, investigation workflows, HRIS integrations, and audit-ready records. | Anonymous digital reporting + investigation |
| **[Red Flag Reporting](https://www.redflagreporting.com/)** | Whistleblower and ethics hotline provider offering reporting channels, case management, and compliance support. | Ethics hotline & reporting |

---

## Open-Source Softwares

Whistleblower and secure anonymous reporting has strong open-source options, especially for high-security and media/activist use cases. Two projects stand out globally.

### Core Frameworks & Whistleblowing Platforms

| Project | Description | License | Notes |
|---------|-------------|---------|-------|
| **[GlobaLeaks](https://github.com/globaleaks/GlobaLeaks)** | Free and open-source software for secure and anonymous whistleblowing platforms. Supports Tor Onion Services, encryption, strict data retention, multilingual interfaces, and compliance with EU Whistleblower Directive, GDPR, and ISO standards. Used by thousands of organizations including public authorities and NGOs. | AGPL | Leading open-source whistleblowing platform |
| **[SecureDrop](https://github.com/freedomofpress/securedrop)** | Open-source whistleblower submission system designed for media organizations to securely accept documents and communicate with anonymous sources via Tor. Strong emphasis on minimizing metadata and protecting sources. Managed by Freedom of the Press Foundation. | Free & open source | Gold standard for journalism / high-security submissions |
| **Related secure messaging & Tor tools** | Components and best practices from the Tor Project, Onion services, and privacy-focused operating systems (Tails, Qubes) commonly recommended alongside GlobaLeaks and SecureDrop. | Various | Supporting privacy infrastructure |
| **Custom secure forms + case tools** | Combinations of open form platforms, encrypted storage, and ticketing systems adapted for anonymous intake (less secure than purpose-built solutions). | Various | Lightweight / experimental setups |

### Specialized Libraries & Related Tools

| Project | Description | Focus Area |
|---------|-------------|---------|
| **Tor & Onion services** | Core anonymity network used by both GlobaLeaks and SecureDrop for source protection. | Anonymity layer |
| **Encryption & secure storage** | Open cryptographic libraries and encrypted database patterns for protecting submissions at rest. | Data protection |
| **Case / ticket systems** | Open-source issue trackers (e.g., adapted Request Tracker, Zammad, or custom) that can serve as investigation backends. | Case management |
| **Audit logging** | Open tools for immutable or append-only logging of case actions to support compliance. | Audit trails |
| **Multilingual & accessibility** | Localization frameworks and WCAG-oriented front ends used in GlobaLeaks (70+ languages). | Inclusivity & compliance |
| **Secure OS recommendations** | Tails and Qubes OS documentation and tooling frequently paired with these platforms for maximum source and recipient security. | Endpoint security |

### Additional Notable Open-Source Tools

- **Self-hosted GlobaLeaks deployments** — Organizations can run fully controlled instances with custom branding, retention policies, and recipient workflows while meeting EU Directive and GDPR requirements.
- **SecureDrop for newsrooms** — Purpose-built for journalistic source protection with dedicated hardware recommendations and rigorous operational security guidance.
- **Hybrid approaches** — Some organizations combine GlobaLeaks for anonymous intake with commercial or open case-management tools for investigation workflows.
- **Privacy-enhancing add-ons** — Integration patterns with encrypted email, secure drop boxes, and metadata-stripping tools.
- **Compliance documentation** — Open guidance and checklists aligned with ISO 37002, EU Whistleblower Directive 2019/1937, and accessibility standards.
- **Community & NGO deployments** — Extensive real-world use by anti-corruption authorities, media outlets, and civil-society organizations worldwide.

**Note:** Commercial platforms excel at polished enterprise case management, 24/7 phone hotlines, HRIS/GRC integrations, training modules, and turnkey compliance reporting. Open-source solutions (especially GlobaLeaks and SecureDrop) provide superior anonymity guarantees, full data ownership, transparency, and zero licensing cost, making them the preferred choice for high-security, journalistic, governmental, and activist use cases. Many regulated organizations successfully run GlobaLeaks in production.

---

## Quick Start Recommendations

| Goal | Recommended Starting Point |
|------|---------------------------|
| Best overall open-source whistleblowing platform | **GlobaLeaks** |
| Maximum source protection for journalism | **SecureDrop** |
| Enterprise ethics & compliance suite | **NAVEX One / EthicsPoint** |
| Modern anonymous reporting + investigation | **AllVoices** |
| Strong EU / multilingual enterprise focus | **EQS Integrity Line** or **People Intouch** |
| Ethics platform with GRC integration | **Convercent (OneTrust)** |
| Independent hotline service | **Safecall** |
| User-friendly speak-up portal | **FaceUp** or **WhistleB** |
| Classic third-party hotline | **EthicsPoint** or **Red Flag Reporting** |

---

## Contributing

Contributions, corrections, and new open-source projects are welcome.  
Please open an issue or pull request.

---

**Last updated:** August 2026  
Emphasizing open-source tools while documenting the major commercial platforms for context. GlobaLeaks is the leading open-source whistleblowing platform used by tens of thousands of organizations; SecureDrop remains the gold standard for secure journalistic source submissions. Commercial platforms dominate enterprise case management, phone hotlines, and integrated compliance suites.
