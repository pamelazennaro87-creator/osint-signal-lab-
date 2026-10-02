# EU Jurisdictional Seam — Azure Data in Netherlands & Ireland

**Status:** INSTITUTIONAL / CORROBORATED  
**Layer:** Infrastructure location → regulatory exposure → governance aftershock  
**Boundary:** No person-level attribution. Institutional and geographic facts only.

## Core claim

Public reporting places a large volume of Israeli military / Unit 8200–related surveillance data on **Microsoft Azure servers in the Netherlands** (primary) and **Ireland** (secondary). Both are EU jurisdictions. This creates a documented **jurisdictional seam**: SIGINT collection outside the EU, storage and processing inside EU data-protection space.

## Public evidence cluster

| Element | Source type | What it establishes |
|---------|-------------|---------------------|
| ~11,500 TB of Israeli military data on Azure NL (equiv. ~200m hours audio) by mid-2025 | Guardian / +972 / Local Call (Aug 2025) + Microsoft review statements | Scale and primary location |
| Smaller share in Ireland | Same investigation | Secondary EU location |
| Data moved out of Netherlands within days of Aug 2025 report | Guardian follow-ups | Rapid relocation under pressure |
| Planned / reported shift toward AWS | Intelligence sources cited in Guardian | Hyperscaler pivot |
| Microsoft ceased specified cloud storage and AI services to Unit 8200 (Sep 2025) | Microsoft (Brad Smith) | Service termination |
| External review closed; findings stand (Jun 2026) | Microsoft public update | Confirmed limitation |
| Protest on roof of Microsoft data centre (Middenmeer / North Holland) | Guardian, Geef Tegengas | Civil society reaction at physical site |
| Dutch parliamentary questions on storage at Middenmeer | Official Q&A (Tweede Kamer) | National political attention |
| Complaint pathway toward Irish DPC (Microsoft HQ jurisdiction) | Reporting on Eko / civil-society filings | Lead GDPR authority exposure |

## Why this is under-connected

Most coverage treats either:
- the **surveillance system** (calls, targeting), or
- the **Microsoft cut** (corporate decision),

as separate stories. The **location of the servers inside the EU** is rarely drawn as a single analytical object:

```
SIGINT collection (outside EU)
    → storage/processing on Azure NL + IE (inside EU)
        → GDPR / national political / civil-society exposure
            → service termination + data relocation + hyperscaler pivot
```

This is a **capability continuity under jurisdictional friction**, not only a privacy scandal.

## Analytical use for the laboratory

- **INSTITUTIONAL:** Link 8200/Aman → commercial cloud (Microsoft) → EU territory.
- **NOT personal:** Does not identify any anonymized officer.
- **Governance aftershock:** EU location turned a military–commercial arrangement into a multi-jurisdiction regulatory and political problem (NL site, IE lead authority, Microsoft global ToS).
- **Dependency test:** When one hyperscaler cuts access, reporting indicates a shift toward another (AWS). Capability does not disappear; infrastructure provider changes.

## UNRESOLVED

- Exact current location of the relocated dataset (post-NL move).
- Whether AWS or other providers accepted equivalent workloads under what terms.
- Full content of Microsoft external review (public summary only).

## Sources (primary public anchors)

- Guardian / +972 / Local Call investigation series (Aug–Sep 2025)
- Microsoft statements (Sep 2025 service action; Jun 2026 review close)
- Dutch parliamentary answers on Middenmeer storage questions
- Reporting on Geef Tegengas protest and Irish DPC-related complaints

---

*Evidence-first. Location and institutional friction only. No inference across the attribution boundary.*
