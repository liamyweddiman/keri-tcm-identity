# Use Case: KERI for TCM Practitioner Credential Governance and Herbal Medicine Provenance
**Author:** Liam YW Eddiman  
**Status:** Draft for KERI Working Group  
**Tags:** Healthcare Identity, Cultural Identity, Provenance, Supply Chain, TCM

---

## 1. Summary  
This use case proposes applying **KERI (Key Event Receipt Infrastructure)** to two interconnected domains in the Traditional Chinese Medicine (TCM) ecosystem:

1. **Practitioner Credential Governance**  
2. **Herbal Medicine Batch Provenance**

Both domains require strong identity models, verifiable histories, cross-border interoperability, and culturally-informed trust frameworks. KERI’s event-based architecture provides a native model to represent these complex identity flows.

---

## 2. Background & Motivation

### 2.1 Practitioner Credentialing Challenges
TCM practitioners face:
- Diverse training pathways (university programs, lineage-based apprenticeship)
- Inconsistent credentialing standards across jurisdictions
- Difficulty verifying master–apprentice lineage claims
- Limited interoperability of medical licenses
- Weak digital representation of cultural identity attributes

### 2.2 Herbal Medicine Provenance Challenges
The herbal supply chain suffers from:
- Mixed or unknown-origin materials  
- Counterfeit or substituted herbs  
- Loss of provenance during processing  
- Poor visibility of laboratory testing results  
- Complex international export pathways  

KERI can support batch-level, event-authenticated provenance.

---

## 3. Stakeholders

### Practitioner Identity
- Practitioners  
- Lineage holders / masters  
- Universities & TCM hospitals  
- National medical boards  
- International accreditation bodies  
- Patients  

### Herbal Provenance
- Farmers  
- Processing facilities  
- Laboratory testing agencies  
- Export authorities  
- Pharmaceutical manufacturers  
- Regulators  

---

## 4. Practitioner Identity Event Chain (Conceptual)

1. **Inception Event**  
   - Practitioner AID created  
   - Witnesses recorded  

2. **Lineage Attestation Event**  
   - Masters or lineage holders sign apprenticeship relationships  

3. **Training / Education Events**  
   - Universities, hospitals, or CE programs sign completion events  

4. **License Issuance Event**  
   - National or regional medical boards attest scope of practice  

5. **Cross-border License Binding**  
   - Practical for AU/EU/US/ASEAN equivalence mapping  

6. **Renewal / CE / Compliance Events**  
   - Periodic training, credit hours  

7. **Disciplinary or Suspension Events**  

8. **Revocation Event (if applicable)**  

This chain encodes cultural identity (lineage) + healthcare identity (professional licensing).

---

## 5. Herbal Medicine Provenance Event Chain (Conceptual)

1. **Batch Inception Event**  
   - Farm or regional coop creates batch AID  

2. **Harvest Event**  
   - Date, geo-location, crop variety  

3. **Processing Events**  
   - Drying, extraction, fermentation, compounding  

4. **Laboratory QC Events**  
   - Purity, safety, heavy metals, microbial testing  

5. **Packaging & Lot Creation Event**  

6. **Export Certification Event**  

7. **Manufacturer Receipt Event**  
   - Batch identity validated prior to use  

This chain provides end-to-end verifiable provenance.

---

## 6. Why KERI?  
- Event-based identity fits long-lived professional identities  
- Witness receipts provide strong cryptographic auditability  
- Supports cultural elements such as lineage attestation  
- Enables global interoperability for practitioner mobility  
- Creates transparent provenance records for regulated products  
- Does not require blockchain, suitable for national healthcare systems  

---

## 7. Proposed Next Steps  
- Align practitioner event types with healthcare credential standards  
- Draft provisional schemas for lineage, training, and license events  
- Draft herbal provenance event schema (batch–lot mapping)  
- Explore compatibility with ACDC data containers  
- Propose interoperable credential types for regulators  

---

## 8. Contribution Intent  
This document is offered as a starting point for discussion and refinement.  
I am happy to contribute further documentation, schemas, and prototype diagrams  
if this direction aligns with the KERI working group’s interests.

**— Liam YW Eddiman**
