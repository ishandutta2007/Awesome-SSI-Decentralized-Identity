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
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Platform / Product | Description & Focus | Starting Tier Price | Free Tier / Free Trial Limits |
| :--- | :--- | :--- | :--- |
| **[Dock Labs (Truvera)](https://www.dock.io/)** | Turnkey verifiable credential platform & APIs for issuing, verifying, and building reusable identity and KYC workflows. | **$499 / month** (Build plan for PoC, pilot, and starter production) | **30-day free trial** with unlimited credential issuance & verification in test sandbox. |
| **[Affinidi](https://www.affinidi.com/)** | Decentralized identity & consent-based data-sharing platform with developer SDKs and Login integration. | **$199 / month** (Developer / Pro tier with bundled Affinidi Credit packages) | **Free Essential Plan** (Forever free; starter allocation of Affinidi Credits and MAU allowance for testing). |
| **[Trinsic](https://trinsic.id/)** | Reusable identity acceptance network & developer infrastructure for issuing and accepting trusted credentials. | **$99 / month** (Growth plan with 1,000 credential transactions included; or ~$1.50/verification) | **Free Developer Plan** (Forever free; up to 100 credentials/month with Mock Providers & Tester Network). |
| **[Paradym (by Animo)](https://paradym.id/)** | Enterprise SSI platform built on Credo/Aries & OpenID4VC for issuing, requesting, and verifying verifiable credentials. | **€50 / month** (Builder plan including 2,000 transactions/month; €0.033 per extra transaction) | **Free Community Plan** (Forever free; 100 transactions/month with full OpenID4VC & AnonCreds support). |
| **[Danube Tech (Godiddy)](https://godiddy.com/)** | Cloud SSI services providing Universal Resolver, Registrar, and DID/VC management infrastructure. | **€60 / month** (T1 tier including 2,000 transactions/month; €0.03 per extra transaction) | **Free Tier** (Forever free; max 10 requests/30 mins, 5 total testnet DID writes, 2 DIDs/month). |
| **[cheqd Studio](https://cheqd.io/)** | SSI network tooling, payment rails, and developer APIs to monetize and exchange credentials and DIDs. | **~$2.00 / DID write** (Mainnet DID write ~$2.00, update ~$1.00, resources ~$0.10–$0.40 in $CHEQ token) | **Free Testnet Tier** (Forever free unlimited DID creation, registration, and credential writes on testnet). |
| **[walt.id Enterprise](https://walt.id/)** | Enterprise-grade managed cloud & turnkey SSI infrastructure with high availability and SLA support. | **€2,500 / month** (Enterprise Managed Cloud/SaaS with clustering, multi-tenancy & enterprise support) | **Free Community Stack** (Forever free self-hosted open-source core with unlimited DIDs/VCs; 14-day cloud trial). |
| **[Validated ID (VIDsigner)](https://www.validatedid.com/)** | Qualified trust service provider offering digital identity verification and eIDAS-compliant verifiable credentials. | **€20 / month per user** (Business plan including 5 advanced signature credits/month) | **14-day free trial** (Full Business tier features with 5 signature credits, no credit card required). |
| **[Sphereon](https://sphereon.com/)** | Enterprise SSI and verifiable data exchange (VDX) platform, agent orchestration, and wallet SDKs. | **€500 / month** (Starter enterprise pilot & verifiable data exchange API package) | **Free Forever Wallet App & Demo Portal** (Unlimited credential storage in wallet apps and full access to sandbox demo). |
| **[Lissi](https://www.lissi.id/)** | European Digital Identity (EUDI) Wallet connector and enterprise SSI interaction platform. | **€1,500 / month** (Starter Program pilot package for EUDI Wallet & eIDAS 2.0 integration) | **30-day interactive pilot trial** (Includes sandbox environment, test credentials, and SDK integration access). |

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
