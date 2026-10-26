# Awesome-Electronic-Signature-E-Signature
<<<<<<< HEAD

=======
>>>>>>> 1944e01810b511db2b8c509d080371d7b4356bf8
# Top Electronic Signature (E-Signature) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Digital Document Signing, Workflow Automation & Legal Compliance*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Electronic Signature (E-Signature)**. These tools enable organizations to send, sign, track, and manage legally binding digital documents, covering the full signing lifecycle from template creation to audit trail generation and compliance verification.

**Examples** include Adobe Sign, DocuSign, PandaDoc, SignNow, Dropbox Sign, OneSpan Sign, airSlate, Box Sign, Eversign, and Zoho Sign (the category leaders).

**Open-source emphasis**: This section is heavily expanded with active projects for self-hosted document signing, PDF cryptographic signing, multi-signer workflows, and audit trail management — ideal for enterprises, legal teams, and developers building sovereign e-signature infrastructure without per-envelope pricing lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Adobe Sign](https://www.adobe.com/sign.html)**  
  Enterprise e-signature solution integrated with Adobe Acrobat and Experience Cloud, offering workflows, forms, and compliance with global regulations.

- **[DocuSign](https://www.docusign.com/)**  
  The market-leading e-signature platform with Agreement Cloud, identity verification, and extensive integrations for enterprise document workflows.

- **[PandaDoc](https://www.pandadoc.com/)**  
  Document automation and e-signature platform combining proposals, contracts, and signing workflows with CRM integrations.

- **[SignNow](https://www.signnow.com/)**  
  E-signature platform with mobile-friendly signing, templates, and workflow automation for teams and enterprises.

- **[Dropbox Sign](https://sign.dropbox.com/)**  
  E-signature service (formerly HelloSign) integrated with Dropbox, offering simple signing workflows and API access.

- **[OneSpan Sign](https://www.onespan.com/)**  
  Enterprise e-signature and digital transaction management platform with strong authentication and compliance features.

- **[airSlate](https://www.airslate.com/)**  
  Document workflow automation platform with e-signature, robotic process automation, and no-code workflow builder.

- **[Box Sign](https://www.box.com/box-sign)**  
  E-signature capability built into Box content cloud, enabling signing directly from stored documents.

- **[Eversign](https://eversign.com/)**  
  E-signature platform (formerly SignEasy) with templates, team management, and API for small to mid-sized businesses.

- **[Zoho Sign](https://www.zoho.com/sign/)**  
  E-signature solution integrated with Zoho ecosystem, offering document signing, templates, and audit trails.

## Open-Source GitHub Projects

- **[DocuSeal](https://github.com/docusealco/docuseal)**  
  Leading open-source DocuSign alternative with WYSIWYG PDF form builder, AI-powered field detection, multi-party signing, and compliance with ESIGN/UETA/eIDAS; AGPL-3.0 licensed, Docker-deployable with SQLite/PostgreSQL/MySQL support .

- **[OpenSign](https://github.com/OpenSignLabs/OpenSign)**  
  Free and open-source DocuSign alternative with secure PDF e-signing, multi-signer support, templates, OTP verification for guest signers, expiring documents, audit trails, and OpenSign Drive; MIT-licensed, Docker-ready .

- **[Documenso](https://github.com/documenso/documenso)**  
  Transparent, self-hosted DocuSign alternative built with Next.js and PostgreSQL; supports drag-and-drop signature fields, multi-recipient workflows, cryptographic PDF signing with RFC 3161 timestamps, REST API, and OAuth; AGPL-3.0 licensed .

- **[DSS (Digital Signature Service)](https://github.com/esig/dss)**  
  European Commission's open-source library for creating and validating advanced electronic signatures (XAdES, PAdES, CAdES, JAdES, ASiC) with full ETSI standard compliance and trust list validation .

- **[Trexo PDF Signer](https://github.com/trexolab-solution/trexo-pdf-signer)**  
  Professional-grade desktop application for creating legally binding digital signatures on PDFs; supports PKCS#11 hardware tokens, PKCS#12/PFX certificates, smart cards, Windows Certificate Store, and RFC 3161 timestamping .

- **[SuiteOp Sign](https://hub.docker.com/r/jeanlosi/suiteop-sign)**  
  White-labeled fork of Documenso with custom branding and theme; inherits all Documenso features including templates, multi-user support, API access, and self-hosting capability .

- **[OpenSig](https://github.com/OpenSig/opensig)**  
  E-signature web app for digitally signing and verifying documents on EVM-based blockchains, with JavaScript library for publishing signatures .

### Additional Strong Open-Source Options

- **digisign** — PHP library for communication with the digisign.org API using PSR-18 HTTP Client .
- **django-esign** — Django package for processing electronic/digital signatures from humans .
- **esign-app** (digital-blueprint) — Digital signing application with PAdES support for PDF signing and verification .
- **PapSign SDK** — Electronic signature and cryptography SDK for Java .
- **PDF signing scripts** — Community pipelines combining Python libraries (pypdf, pyHanko) with PKCS#11 for automated batch signing workflows.

**Frameworks for building custom systems**: Combine **DocuSeal** or **Documenso** for the web-based signing workflow, **DSS** for advanced cryptographic signature creation and validation, **Trexo PDF Signer** for hardware token-based desktop signing, and **OpenSign** for multi-tenant document management with audit trails in a fully self-hosted e-signature stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- E-signature platforms must comply with applicable regulations (ESIGN Act, UETA, eIDAS, and regional digital signature laws).
- Self-hosted open-source solutions require proper security hardening, certificate management, and legal review for enforceability in target jurisdictions.
- Verify license terms for commercial use; some projects use AGPL-3.0 which may require releasing derivative code if distributed.

---

**Made for enterprises, legal teams, HR departments, and document workflow developers.**  
Let's make electronic signatures more open, verifiable, and accessible.
