# Awesome-SSI-Decentralized-Identity

## Top Decentralized Identity (SSI) Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Self-Sovereign Identity, Verifiable Credentials, DIDs, Wallets, Issuers & Verifiers*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Decentralized Identity (SSI)**. These systems enable issuance, holding, and verification of verifiable credentials (VCs) using decentralized identifiers (DIDs), giving individuals and organizations control over identity data without central silos.

**Examples** include Dock Labs, Affinidi, Trinsic, Sphereon, Veramo, Danube Tech, Validated ID, Lissi, Credo, and cheqd (the category leaders).

**Open-source emphasis**: SSI is built on open standards and has a rich open-source stack. **Hyperledger Aries / Credo**, **Veramo**, **ACA-Py**, **Identus**, **walt.id**, DID resolvers, and wallet frameworks provide production-capable building blocks. This section is heavily expanded with these tools.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Dock Labs](https://www.dock.io/)**  
  Verifiable credential platform with APIs for issuing, verifying, and building reusable identity and KYC use cases.

- **[Affinidi](https://www.affinidi.com/)**  
  Decentralized identity and data-sharing platform focused on developer tools and consent-based credential exchange.

- **[Trinsic](https://trinsic.id/)**  
  Developer platform for reusable identity and verifiable credentials — issue once, accept trusted credentials across products.

- **[Sphereon](https://sphereon.com/)**  
  SSI and verifiable data solutions for enterprises, including agents, wallets, and integration services.

- **[Veramo (commercial / hosted options)](https://veramo.io/)**  
  Hosted and enterprise offerings built on the open Veramo JavaScript framework for verifiable data.

- **[Danube Tech](https://danubetech.com/)**  
  Identity and SSI technology provider with products and services around DIDs, VCs, and related standards.

- **[Validated ID](https://www.validatedid.com/)**  
  Digital identity and electronic signature solutions with SSI and qualified trust service capabilities (EU-focused).

- **[Lissi](https://www.lissi.id/)**  
  SSI wallet and ecosystem components for holding and presenting verifiable credentials.

- **[Credo (OpenWallet Foundation / commercial support)](https://credo.js.org/)**  
  Commercial support and products around the open Credo TypeScript framework for SSI agents.

- **[cheqd](https://cheqd.io/)**  
  Identity network and tooling that supports payment rails between issuers, holders, and verifiers for credential exchange.

## Open-Source GitHub Projects
- **[Veramo](https://github.com/decentralized-identity/veramo)**  
  Modular JavaScript/TypeScript framework for DIDs, verifiable credentials, messaging, and agent-based SSI applications.

- **[Credo (credo-ts)](https://github.com/openwallet-foundation/credo-ts)**  
  TypeScript framework for building decentralized identity and verifiable credential solutions (Aries-compatible agents, wallets, mediators).

- **[Hyperledger Aries / ACA-Py](https://github.com/hyperledger)**  
  Foundational open protocols and agents (including Aries Cloud Agent Python) for interoperable SSI issuers, holders, and verifiers.

- **[Hyperledger Identus](https://github.com/hyperledger-identus)**  
  LF Decentralized Trust project providing cloud agent, mediator, edge SDKs, and components for standards-based SSI solutions.

- **[walt.id](https://github.com/walt-id)**  
  Open-source stack for building end-to-end digital identity use cases, wallets, and EU-aligned credential flows.

- **[Universal Resolver & DID method drivers](https://github.com/decentralized-identity/universal-resolver)**  
  Open resolver and drivers for resolving DIDs across many methods (did:web, did:key, did:ethr, Indy, etc.).

- **[AnonCreds and credential format implementations](https://github.com/)**  
  Open implementations of privacy-preserving credential formats used in many SSI deployments.

- **[Bifold and open mobile wallets](https://github.com/openwallet-foundation)**  
  Open React Native and related wallet projects for holding and presenting credentials on mobile devices.

- **[DIDComm and messaging libraries](https://github.com/)**  
  Open protocols and libraries for secure, decentralized messaging between SSI agents.

- **[Decentralized Identity Foundation (DIF) specs & tools](https://github.com/decentralized-identity)**  
  Working-group repositories for DID, VC, and related interoperability specifications and reference code.

### Additional Strong Open-Source Options
- Building issuer/verifier agents with **Credo** or **ACA-Py** and holding credentials in **Bifold**-style wallets.
- Using **Veramo** for Node/TypeScript services that issue and verify W3C VCs.
- Resolving DIDs via the **Universal Resolver** and hosting did:web documents under your domain.
- Running test networks (e.g. Indy-based or cheqd-style) for development before production ledgers.
- Aligning with W3C DID/VC and OpenID for Verifiable Credentials profiles for interoperability.
- Contributing to OpenWallet Foundation and Hyperledger Identus for shared wallet and agent infrastructure.

**Frameworks for building custom systems**: Combine **Credo** or **Veramo** agents, open wallets (Bifold), DID methods (did:web / did:key / network-specific), and W3C VC formats; optionally use a commercial network or ledger (cheqd, etc.) for discovery and payments. This stack is fully open and standards-aligned. Commercial platforms (Dock, Trinsic, Affinidi, Sphereon, Validated ID, Lissi, etc.) still lead in turnkey APIs, compliance packaging, EU wallet alignment, and enterprise support for production programs.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Decentralized identity involves cryptography, key management, and often regulated credentials (e.g. government ID, professional licenses). Key loss can mean permanent loss of control; recovery and governance design matter. Interoperability is still evolving — test against the specific wallets and verifiers you need. Legal recognition of VCs varies by jurisdiction.
- This list is not legal or compliance advice.

---
**Made for identity architects, wallet builders, and product teams putting control back in the holder’s hands.**
Let's keep decentralized identity open, interoperable, and user-controlled.
