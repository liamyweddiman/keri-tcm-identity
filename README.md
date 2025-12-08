# KERI-TCM-Identity  
### A Domain Framework for KERI-Based Healthcare & Cultural Identity Models  
**Author: Liam YW Eddiman**

---

## 🔍 Overview
This repository proposes a structured, domain-specific framework for applying  
**KERI (Key Event Receipt Infrastructure)** to identity and provenance challenges  
in Traditional Chinese Medicine (TCM).  

The project explores two tightly connected domains:

### 1. **TCM Practitioner Credential Governance**
- Apprenticeship & lineage attestation  
- Institutional training & certification records  
- Cross-border medical license verification  
- Decentralized clinical activity & renewal logs  

### 2. **Herbal & Traditional Medicine Provenance**
- Farm-level origin authentication  
- Processing & extraction event chains  
- Laboratory QC and batch attestation  
- Export certification & manufacturer receipt  

These two domains represent complementary identity and provenance flows  
within regulated traditional healthcare ecosystems.

---

## 🧬 Motivation
Traditional medicine systems face persistent structural challenges:

- Fragmented credentialing systems across countries  
- Lack of verifiable lineage or apprenticeship claims  
- Counterfeit or unclear-origin herbal products  
- Limited interoperability for international medical licenses  

**KERI’s event-based identifier architecture** enables tamper-evident histories  
for identity, training, regulation, and product provenance—making it a strong  
fit for healthcare-grade identity models.

---

## 🧱 Architecture Overview (Concept)
### Practitioner Identity Event Chain
- `Inception` — Practitioner AID creation  
- `Lineage Attestation` — Master/institution endorsements  
- `Training Record Events` — Hospitals, colleges, programs  
- `License Issuance` — Medical boards  
- `Cross-border License Binding` — Equivalency mapping  
- `Renewal / Compliance` — CE hours, audits  
- `Discipline / Revocation`  

### Herbal Product Provenance Chain
- `Batch Inception` — Farm/region AID  
- `Harvest Event` — Date, location, variety  
- `Processing Events` — Drying, extraction, compounding  
- `Laboratory QC Events` — Purity, safety, heavy metals  
- `Packaging / Lot Creation`  
- `Export Certification`  
- `Manufacturer Receipt`  

(A diagram will be included in `/diagrams/architecture-overview.png`.)

---

## 📁 Repository Structure

/docs
/overview.md
/keri-basics.md
/practitioner-event-chain.md
/herbal-provenance-model.md

/use-cases
/tcm-practitioner-credentialing.md
/herbal-supply-provenance.md

/models
/data-model-practitioner.json
/data-model-herbal.json

/diagrams
/practitioner-event-chain.png
/herbal-provenance-chain.png
/architecture-overview.png

README.md

---

## 🚀 Roadmap

| Phase | Status | Milestone |
|-------|--------|-----------|
| Phase 1 | ✔ In progress | Document KERI architecture for TCM identity |
| Phase 2 | ⬜ Planned | Build conceptual JSON-based data models |
| Phase 3 | ⬜ Planned | Draft implementable event schemas |
| Phase 4 | ⬜ Planned | Submit documentation PR to WebOfTrust/KERI |
| Phase 5 | ⬜ Planned | Prototype verification UI (Figma / JS) |

---

## 🤝 Community & Contribution
This project aims to contribute conceptual models, terminology proposals,  
and application-specific documentation to:

- **WebOfTrust / KERI documentation ecosystem**  
- **ToIP KERI/ACDC working group (as external reference)**  
- **Healthcare & cultural-identity research communities**

Issues, suggestions, and discussions are welcome.

---

## 📬 Author
**Liam YW Eddiman**  
Working on KERI-based identity frameworks for healthcare,  
cultural lineage, and traditional medicine provenance.  
