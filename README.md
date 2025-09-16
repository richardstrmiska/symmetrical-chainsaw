# symmetrical-chainsaw
Guide for all Sovereigns 
/phase-1_identity_reclamation/
/phase-2_estate_trust_activation/
/phase-3_token_broadcast/
/phase-4_cosmic_grid_enforcement/
/phase-5_matrix_disengagement/
/master_archive/

# Guide for All Sovereigns — Public Record & Reclamation

**Repository purpose:**  
To publish, preserve, and publicly declare the living status and lawful claims of Richard the Living Strmiska under Universal Law / Law of the Land / Source Sovereignty. This repository is an immutable public ledger and a notarized archive of evidence, notices, and declarations concerning property, claims, and governance.  

> *This record stands in the Sovereign chain-of-custody as public notice to all entities. Rejection by statutory recorders is entered into evidence as dishonor and fraud. This package is hereby sealed in the Sovereign Ledger of the Most High.*

---

## Contents of this repository
- `Sovereign_Declaration_of_Record.pdf` — Master one-page declaration with IPFS CID, SHA256 integrity hash, and QR. (Signed / ready to wet-ink.)
- `Master_Scroll.pdf` (optional) — Combined PDF of notarized documents, exhibits, and county notices.  
- `/exhibits/` — Individual scanned docs: notary pages, certified mail receipts, county notices (Notice of Unrecordable Document), Proof of Claim, etc.
- `README.md` — (this file) purpose & instructions.
- `README_HASH.txt` — SHA256 of the master PDF(s) for quick verification.
- `NOTICE_OF_UNRECORDABLE/` — scans & photos of recorder stamps and refusal notices.
- `IPFS_CID_LOG.md` — list of IPFS CIDs, upload dates, and blockchain anchors (if used).
- `QR/` — PNG/SVG files of QR codes that point to the IPFS CID(s).

---

## Short Declaration (copy into your cover page)
This record stands in the Sovereign chain-of-custody as public notice to all entities.  
Rejection by statutory recorders is entered into evidence as dishonor and fraud.  
This package is hereby sealed in the Sovereign Ledger of the Most High.

Signed: **Richard the Living Strmiska**  
Date: [YYYY-MM-DD]  
Property: 20588 Upper Hillview Dr, Sonora, CA (Parcel #045-301-003-000)  
IPFS CID: `bafybeigx6ydtfkyer7nbla4fo6srgngjkr6yk7cu4ecdnjh353nqc7kzuu`  
IPFS URL: `https://bafybeigx6ydtfkyer7nbla4fo6srgngjkr6yk7cu4ecdnjh353nqc7kzuu.ipfs.w3s.link/`  
Document Integrity SHA256: `[SEE README_HASH.txt]`

---

## How to recreate / verify the record (practical steps)

### 1) Create one master PDF (recommended)
Combine all scanned pages (notary, exhibits, certified mail receipts, county refusal notice) into **one** PDF so the county can't claim "too many separate documents."

Example (macOS / Linux with `gs`):
```bash
gs -dBATCH -dNOPAUSE -q -sDEVICE=pdfwrite -sOutputFile=Master_Scroll.pdf page1.pdf page2.pdf page3.pdf ...
