<div align="center">

<a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
<a href="https://github.com/ishandutta2007/Awesome-Electronic-Signature-E-Signature/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Electronic-Signature-E-Signature?style=flat-square&color=gold" alt="GitHub Repo Stars"/></a>
<a href="https://github.com/ishandutta2007/Awesome-Electronic-Signature-E-Signature/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Electronic-Signature-E-Signature?style=flat-square&color=blue" alt="GitHub Forks"/></a>
<a href="https://github.com/ishandutta2007/Awesome-Electronic-Signature-E-Signature/issues"><img src="https://img.shields.io/github/issues/ishandutta2007/Awesome-Electronic-Signature-E-Signature?style=flat-square&color=green" alt="Issues"/></a>
<a href="https://github.com/ishandutta2007/Awesome-Electronic-Signature-E-Signature/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square" alt="License"/></a>
<a href="https://github.com/ishandutta2007/Awesome-Electronic-Signature-E-Signature/pulls"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" alt="PRs Welcome"/></a>
<a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>

<br/><br/>

<a href="https://github.com/ishandutta2007/Awesome-Electronic-Signature-E-Signature">
  <img src="assets/banner.svg" alt="Awesome Electronic Signature E-Signature Banner" width="100%" />
</a>

# 🖋️ Awesome Electronic Signature (E-Signature)

**Curated Directory of Enterprise SaaS Platforms & Open-Source Digital Signature Ecosystems**  
*Covering Document Signing, Cryptographic Verification, PDF Security, eIDAS & ESIGN/UETA Compliance, and Self-Hosted DocuSign Alternatives.*

</div>

---

## 📑 Table of Contents

- [📊 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [🏢 SaaS & Hosted E-Signature Platforms](#-saas--hosted-e-signature-platforms)
- [💻 Open-Source GitHub Projects](#-open-source-github-projects)
- [🧱 Architectural Blueprint for Custom E-Sign Stacks](#-architectural-blueprint-for-custom-e-sign-stacks)
- [📈 Star History](#-star-history)
- [🤝 How to Contribute](#-how-to-contribute)
- [💖 Support & Community](#-support--community)
- [⚖️ Disclaimer & Legal Compliance](#-disclaimer--legal-compliance)

---

## 📊 Sector Overview & Market Dynamics

The global **Electronic Signature (E-Signature)** market is estimated at **$5.5 Billion to $7.0 Billion** in 2024 and is projected to expand at an aggressive CAGR of **~28%–34%**, exceeding **$25 Billion to $35+ Billion by 2030**. 

From a competitive standpoint, the sector is **moderately concentrated at the enterprise apex**—incumbents **DocuSign** and **Adobe Sign** capture upwards of 65% of Fortune 500 contract workflows. However, the broader market is experiencing rapid fragmentation across specialized mid-market SaaS competitors (such as PandaDoc, airSlate SignNow, and Zoho Sign) alongside a high-velocity migration toward **privacy-first, self-hosted open-source alternatives** (such as DocuSeal, Documenso, and OpenSign). This decentralization is driven by ballooning per-envelope commercial SaaS fees, rigorous data sovereignty mandates (GDPR, eIDAS 2.0), and developer demand for embeddable, transparent REST APIs.

---

## 🏢 SaaS & Hosted E-Signature Platforms

The table below lists leading commercial electronic signature platforms, ranked by **company size / valuation / market capitalization** (descending). All pricing tiers and free limits reflect specific, verified plans.

| 🏢 Platform | 💰 Company Size / Valuation | 🏷️ Starting Tier Pricing | 🎁 Free Tier / Free Trial Limits | ✨ Core Capabilities & Specialization |
| :--- | :--- | :--- | :--- | :--- |
| **[Adobe Sign](https://www.adobe.com/sign.html)** | **~$215B Market Cap**<br/>*(~$21.4B Annual Revenue)* | **$12.99 / month**<br/>*(Acrobat Standard, annual commitment; or $19.99/mo for Acrobat Pro)* | **7-day free trial** of Acrobat Pro (full e-sign tools); free online Adobe account permits **2 free signature transactions / month** | Deep native integration with Adobe Acrobat PDF engine, Microsoft 365, Salesforce; global regulatory compliance (eIDAS, FedRAMP, HIPAA). |
| **[DocuSign](https://www.docusign.com/)** | **~$12.5B Market Cap**<br/>*(~$2.8B Annual Revenue)* | **$10 / month**<br/>*(Personal plan, billed annually at $120/yr; or $15/mo monthly; includes 5 envelopes/mo)* | **Free forever plan** with unlimited self-signing + **3 lifetime sent envelopes total**; **30-day free trial** with unlimited test envelopes | Enterprise agreement cloud, identity verification, smart contracts, conditional routing, and prebuilt enterprise CRM/ERP connectors. |
| **[Dropbox Sign](https://sign.dropbox.com/)** | **~$8.8B Market Cap**<br/>*(~$2.5B Annual Revenue)* | **$15 / month**<br/>*(Essentials plan, billed annually at $180/yr; or $20/mo monthly for 1 sender)* | **Free forever plan** with **3 signature requests per 30-day period** (unlimited self-signing); **30-day free trial** for paid plans | Formerly HelloSign; seamless Dropbox cloud storage integration, frictionless developer-friendly embeddable REST API, and signer notifications. |
| **[Box Sign](https://www.box.com/box-sign)** | **~$4.8B Market Cap**<br/>*(~$1.04B Annual Revenue)* | **$5 / user / month**<br/>*(Box Starter, billed annually, min 3 users, 10 e-sign docs/user/mo; or $15/user/mo Business for unlimited)* | **Free forever Box Individual plan** includes **5 e-sign document requests / month**; **14-day free trial** on all Business tiers | Native electronic signature capability directly inside Box Cloud Content Management; zero external data routing, unified enterprise governance. |
| **[Zoho Sign](https://www.zoho.com/sign/)** | **~$1.2B+ Annual Revenue**<br/>*(Privately held / bootstrapped)* | **$10 / user / month**<br/>*(Standard plan, billed annually at $120/yr; or $12/user/mo monthly)* | **Free forever plan** for 1 user with **5 envelopes / month**; **14-day free trial** of Enterprise plan (up to 50 envelopes, 10 users) | Tight synergy with Zoho CRM, People, and Books; Aadhaar eSign (India), cryptographic timestamping, blockchain timestamp verification, and REST APIs. |
| **[airSlate](https://www.airslate.com/)** | **$1.25B Valuation**<br/>*(Unicorn; backed by Gsquare & UiPath)* | **$399 / month**<br/>*(Growth Plan, billed annually, 10,000 automation credits/flows for end-to-end orchestration)* | **Free tier workspace** includes **10 automation credits / month**; **30-day free trial** for custom workflow automation | Comprehensive no-code business process automation combining robotic process automation (RPA), contract generation, and e-signatures. |
| **[PandaDoc](https://www.pandadoc.com/)** | **$1.0B Valuation**<br/>*(Unicorn; backed by One Peak & M12)* | **$19 / user / month**<br/>*(Starter plan, billed annually; or $35/user/mo monthly; includes 5 reusable templates)* | **Free eSign plan** with **5 documents / calendar month**, max 2 recipients, 5 templates; **14-day free trial** with full Starter/Business features | Interactive proposals, quoting software (CPQ), integrated payment collection (Stripe/PayPal), and document engagement tracking analytics. |
| **[Eversign (Xodo Sign)](https://eversign.com/)** | **~$1.0B Valuation**<br/>*(Apryse / PDFTron, backed by Thoma Bravo)* | **$9.99 / user / month**<br/>*(Basic plan, billed annually; or $14.99/mo monthly; unlimited documents, 3 templates)* | **Free forever plan** includes **5 documents / month** (capped at 1 document per 7 days) and 1 template; **14-day free trial** for paid plans | Acquired and rebranded under Xodo/Apryse; in-person signing kiosk mode, audit trail certificates, API access, and secure cloud storage. |
| **[OneSpan Sign](https://www.onespan.com/)** | **~$450M Market Cap**<br/>*(NASDAQ: OSPN; ~$235M Annual Revenue)* | **$20 / user / month**<br/>*(Professional Plan, billed annually at $240/yr; up to 1,000 transactions/yr)* | **30-day free trial** (up to 100 document transactions); **Permanent free developer sandbox** with watermarked API transactions | Bank-grade security and authentication, digital transaction management (DTM), white-label branding, and government/defense grade identity verification. |
| **[SignNow](https://www.signnow.com/)** | **Part of airSlate ($1.25B)**<br/>*(airSlate subsidiary)* | **$8 / user / month**<br/>*(Business plan, billed annually at $96/yr; or $20/user/mo monthly)* | **7-day free trial** with full document sending and signing access; paid plans baseline **100 signature invites / user / year** | Cost-effective SMB & team document routing, fillable field generation, multi-party signing order, and cross-platform mobile apps (iOS & Android). |

---

## 💻 Open-Source GitHub Projects

Explore top-tier open-source document signing engines, PDF cryptographic libraries, and web-based DocuSign alternatives. Repositories are **sorted by GitHub Stars_Count (descending)**.

- **[DocuSeal](https://github.com/docusealco/docuseal)** [![GitHub_Stars](https://img.shields.io/github/stars/docusealco/docuseal?style=social&color=white)](https://github.com/docusealco/docuseal/stargazers)  
  *The leading open-source DocuSign alternative.* Features a drag-and-drop WYSIWYG PDF form builder, automated field detection, multi-party signing sequences, mobile responsiveness, and ESIGN/UETA/eIDAS compliance. Licensed under AGPL-3.0 with lightweight Docker deployment supporting PostgreSQL, MySQL, and SQLite.

- **[Documenso](https://github.com/documenso/documenso)** [![GitHub_Stars](https://img.shields.io/github/stars/documenso/documenso?style=social&color=white)](https://github.com/documenso/documenso/stargazers)  
  *The modern, transparent open-source e-signature platform.* Built on Next.js, TypeScript, Prisma, and PostgreSQL. Provides cryptographic PDF signing with RFC 3161 timestamps, custom branding, public API keys, webhooks, and team access control. AGPL-3.0 licensed.

- **[Signature Pad](https://github.com/szimek/signature_pad)** [![GitHub_Stars](https://img.shields.io/github/stars/szimek/signature_pad?style=social&color=white)](https://github.com/szimek/signature_pad/stargazers)  
  *HTML5 canvas-based smooth electronic signature drawing library.* Uses variable-width Bézier curves for natural-looking digital ink signatures on mobile, desktop, and tablets. MIT licensed.

- **[OpenSign](https://github.com/OpenSignLabs/OpenSign)** [![GitHub_Stars](https://img.shields.io/github/stars/OpenSignLabs/OpenSign?style=social&color=white)](https://github.com/OpenSignLabs/OpenSign/stargazers)  
  *Free and open-source document signing solution.* Features multi-signer workflows, PDF template management, OTP guest verification, expiring sign links, detailed audit trails, and OpenSign Drive cloud storage. MIT licensed.

- **[PDF Editor](https://github.com/ShizukuIchi/pdf-editor)** [![GitHub_Stars](https://img.shields.io/github/stars/ShizukuIchi/pdf-editor?style=social&color=white)](https://github.com/ShizukuIchi/pdf-editor/stargazers)  
  *Browser-based offline PDF editor and signer.* Enables users to sign documents, place signatures, annotate, and add fields directly on the client side without uploading files to remote servers. MIT licensed.

- **[Digital Signature Service (DSS)](https://github.com/esig/dss)** [![GitHub_Stars](https://img.shields.io/github/stars/esig/dss?style=social&color=white)](https://github.com/esig/dss/stargazers)  
  *Official European Commission open-source cryptographic framework.* Supports creation and validation of advanced and qualified electronic signatures (PAdES, XAdES, CAdES, JAdES, ASiC) compliant with EU Regulation No 910/2014 (eIDAS) and ETSI technical standards. LGPL-2.1 licensed.

- **[Node SignPDF](https://github.com/vbuch/node-signpdf)** [![GitHub_Stars](https://img.shields.io/github/stars/vbuch/node-signpdf?style=social&color=white)](https://github.com/vbuch/node-signpdf/stargazers)  
  *Lightweight Node.js library for cryptographic PDF signing.* Injects digital signatures, certificate byte ranges, and PKCS#7 / CMS signatures into PDF files on the backend. MIT licensed.

- **[LibreSign](https://github.com/LibreSign/libresign)** [![GitHub_Stars](https://img.shields.io/github/stars/LibreSign/libresign?style=social&color=white)](https://github.com/LibreSign/libresign/stargazers)  
  *Sovereign e-signature app for Nextcloud.* Provides self-hosted digital signing, verification, PDF form filling, and cryptographic validation directly within enterprise private cloud environments. AGPL-3.0 licensed.

- **[SignaturePDF](https://github.com/24eme/signaturepdf)** [![GitHub_Stars](https://img.shields.io/github/stars/24eme/signaturepdf?style=social&color=white)](https://github.com/24eme/signaturepdf/stargazers)  
  *Self-hosted web platform for collaborative PDF signing.* Allows single or multi-recipient document signing, page management, metadata editing, and PDF compression. AGPL-3.0 licensed.

- **[pyHanko](https://github.com/MatthiasValvekens/pyHanko)** [![GitHub_Stars](https://img.shields.io/github/stars/MatthiasValvekens/pyHanko?style=social&color=white)](https://github.com/MatthiasValvekens/pyHanko/stargazers)  
  *CLI and Python library for cryptographic signing and stamping of PDF files.* Full support for PAdES, hardware PKCS#11 security tokens, RFC 3161 timestamps, validation records (DSS/LTV), and trust-list evaluation. MIT licensed.

- **[React Signature Canvas](https://github.com/agilgur5/react-signature-canvas)** [![GitHub_Stars](https://img.shields.io/github/stars/agilgur5/react-signature-canvas?style=social&color=white)](https://github.com/agilgur5/react-signature-canvas/stargazers)  
  *Lightweight, high-performance React component wrapper around signature_pad.* Ideal for embedding tactile touch/mouse signature collection into modern web applications. MIT licensed.

- **[JSignPdf](https://github.com/intoolswetrust/jsignpdf)** [![GitHub_Stars](https://img.shields.io/github/stars/intoolswetrust/jsignpdf?style=social&color=white)](https://github.com/intoolswetrust/jsignpdf/stargazers)  
  *Cross-platform desktop application and command-line tool for PDF digital signing.* Features visible signature placement, PKCS#11 and PKCS#12 keystore support, RFC 3161 timestamping, and long-term validation (LTV). LGPL licensed.

- **[SignServer Community Edition](https://github.com/Keyfactor/signserver-ce)** [![GitHub_Stars](https://img.shields.io/github/stars/Keyfactor/signserver-ce?style=social&color=white)](https://github.com/Keyfactor/signserver-ce/stargazers)  
  *Enterprise PKI-based signing server software by Keyfactor.* Automates server-side signing of documents (PDF, XML, Office), code, and time-stamping authorities with hardware security module (HSM) support. LGPL-2.1 licensed.

- **[Trexo PDF Signer](https://github.com/trexolab-solution/trexo-pdf-signer)** [![GitHub_Stars](https://img.shields.io/github/stars/trexolab-solution/trexo-pdf-signer?style=social&color=white)](https://github.com/trexolab-solution/trexo-pdf-signer/stargazers)  
  *Desktop client for legally binding PDF signatures.* Supports PKCS#11 hardware USB tokens, PKCS#12/PFX certificates, Windows Certificate Store, and RFC 3161 time-stamping. MIT licensed.

- **[OpenSig](https://github.com/OpenSig/opensig)** [![GitHub_Stars](https://img.shields.io/github/stars/OpenSig/opensig?style=social&color=white)](https://github.com/OpenSig/opensig/stargazers)  
  *Decentralized e-signature web application for signing and notarizing documents on EVM blockchains.* Anchors cryptographic document hashes to public distributed ledgers. MIT licensed.

- **[DigiSign PHP](https://github.com/digitalcz/digisign)** [![GitHub_Stars](https://img.shields.io/github/stars/digitalcz/digisign?style=social&color=white)](https://github.com/digitalcz/digisign/stargazers)  
  *PHP API client library for DigiSign e-signature automation.* PSR-18 compliant client for managing envelopes, signers, and signature verification. MIT licensed.

- **[django-esign](https://github.com/RecursionSpace/django-esign)** [![GitHub_Stars](https://img.shields.io/github/stars/RecursionSpace/django-esign?style=social&color=white)](https://github.com/RecursionSpace/django-esign/stargazers)  
  *Reusable Django package for handling document signing workflows.* Captures electronic human signatures with audit trail logging in Django web applications. BSD licensed.

- **[esign-app](https://github.com/digital-blueprint/esign-app)** [![GitHub_Stars](https://img.shields.io/github/stars/digital-blueprint/esign-app?style=social&color=white)](https://github.com/digital-blueprint/esign-app/stargazers)  
  *PAdES digital signing application for PDF documents.* Supports electronic signing, validation certificates, and document archiving. Apache-2.0 licensed.

---

## 🧱 Architectural Blueprint for Custom E-Sign Stacks

Building a custom, self-hosted, sovereign electronic signature infrastructure without commercial SaaS envelope lock-in? Here is the battle-tested open-source reference architecture:

```
┌────────────────────────────────────────────────────────┐
│                   USER & SIGNER UI                     │
│    DocuSeal / Documenso (Web)  •  Trexo (Desktop)      │
│          Embedded Pad: React Signature Canvas          │
└───────────────────────────┬────────────────────────────┘
                            │
┌───────────────────────────▼────────────────────────────┐
│              WORKFLOW & AUDIT ORCHESTRATION            │
│   OpenSign Drive / Documenso API • Multi-Signer Queue  │
│   SHA-256 Audit Trail • SMS/Email OTP Guest Signers    │
└───────────────────────────┬────────────────────────────┘
                            │
┌───────────────────────────▼────────────────────────────┐
│          CRYPTOGRAPHIC SIGNING & TIMESTAMPING          │
│   European Commission DSS  •  pyHanko  •  SignServer   │
│   PAdES / XAdES  •  RFC 3161 TSAs  •  HSM / PKCS#11    │
└────────────────────────────────────────────────────────┘
```

1. **Frontend Capture & Form Placement**: Use **[DocuSeal](https://github.com/docusealco/docuseal)** or **[Documenso](https://github.com/documenso/documenso)** for drag-and-drop form creation and responsive signer interfaces.
2. **Cryptographic Validation & Long-Term Archiving**: Integrate **[DSS (Digital Signature Service)](https://github.com/esig/dss)** or **[pyHanko](https://github.com/MatthiasValvekens/pyHanko)** to generate legally binding PAdES-LTV (Long Term Validation) signatures with RFC 3161 timestamps.
3. **Hardware Keys & Key Stores**: Employ **[Trexo PDF Signer](https://github.com/trexolab-solution/trexo-pdf-signer)** or **[SignServer CE](https://github.com/Keyfactor/signserver-ce)** for PKCS#11 USB smart cards and HSM-backed automated enterprise batch signing.

---

## 📈 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Electronic-Signature-E-Signature&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Electronic-Signature-E-Signature&type=date&legend=top-left)

---

## 🤝 How to Contribute

Contributions are welcome! Help expand and refine this ecosystem guide:

1. **Fork** the repository on GitHub.
2. **Add or update** entries in `README.md` adhering to the existing format.
3. **Include**: Platform/Repo name, website/repo link, verified pricing & free tier limits (for SaaS), or valid GitHub repo link and license (for open-source).
4. **Submit a Pull Request** with a concise description of your changes.

Check out [Awesome-Awesome-Awesome](https://github.com/ishandutta2007/AwesomeAwesome-Awesome) for more curated lists!

---

## 💖 Support & Community

Thank you for exploring **Awesome Electronic Signature (E-Signature)**! If this directory assists your engineering, legal, or product architecture decisions:

- ⭐ **Star this repository** to improve visibility across the open-source community.
- 🍴 **Fork and share** with colleagues, dev teams, and legal engineers.
- 💬 **Join our discussions** on Discord or open a GitHub Issue for feature requests.
- ☕ **Support continuous updates & curation** by sponsoring the project:

<div align="center">

<a href="https://github.com/sponsors/ishandutta2007">
  <img src="https://img.shields.io/badge/Sponsor-%E2%99%A5%20ishandutta2007-ea4aaa?style=for-the-badge&logo=github-sponsors&logoColor=white" alt="Sponsor ishandutta2007 on GitHub Sponsors" />
</a>

<br/>

*Visit the official [GitHub Sponsors Dashboard](https://github.com/sponsors/ishandutta2007) to support maintenance.*

</div>

---

## ⚖️ Disclaimer & Legal Compliance

- **Community Curated Resource**: This compilation is maintained for educational and architectural reference only. It does not constitute legal counsel or formal endorsement.
- **Legal Enforceability**: Electronic signatures must comply with regional legislation—including the **U.S. ESIGN Act & UETA**, European **eIDAS Regulation (EU No 910/2014)**, and national digital identity statutes.
- **Security & Governance**: Self-hosted deployments require diligent certificate lifecycle management, root-of-trust verification, tamper-evident audit log safeguarding, and periodic penetration testing.
- **Licensing Compliance**: Always review software licenses prior to commercial integration (e.g., AGPL-3.0, LGPL-2.1, MIT, Apache-2.0).
