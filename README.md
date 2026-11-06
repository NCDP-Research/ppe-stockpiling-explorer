# PPE & antiviral stockpiling — EDGAR 10-K explorer

**→ [Open the explorer](https://ncdp-research.github.io/ppe-stockpiling-explorer/)**

A searchable view of 4,105 annual-report documents from 1,483 US public
companies, filed 2001–2026, asking a single question: does any company hold
protective equipment or antiviral drugs for its own workforce against a future
emergency, and is any incentive aimed at making it do so?

## What it found

- **5 companies** describe holding a stock of PPE for their own people
- **2 companies** describe acting on PPE supply against a future event
- **17 incentive passages across 9 companies** survived individual review
- **46 companies** describe emergency preparedness involving PPE, of which
  **one** ties it to holding any

Preparedness in these filings is a process — plans, drills, crisis teams — not
an inventory. That gap is the finding.

## How to read the numbers

Figures labelled *candidates* are review queues, not findings: they mean a term
appeared near a topic mention, outside boilerplate. Only rows tagged
**verified** were read individually. Expand any row to see the passage and a
link to the exact document on sec.gov.

Several headline figures were corrected during the work. The verified incentive
count fell from 18 to 17 once a body-armour manufacturer was removed from the
PPE population — its "personal protection equipment" is ballistic plates, not
masks.

Four ambiguities in this corpus each produced real false positives:

- **"PPE"** also means property, plant & equipment, "stock" meaning equity, and
  occasionally a counterparty's name
- **The phrase names three unrelated product families** — infection control,
  body armour, motorsport impact gear. Only the first is in scope.
- **"Stockpile"** usually means a pile of ore or frac sand
- **A "document" is not a filing** — 200 of the 4,105 are exhibits, and 14
  describe a different company from the filer

## Source

Built from SEC EDGAR full-text search over 10-K and 10-K/A filings. The
extraction and classification pipeline, and the full methodological write-ups,
are in a private repository (`NCDP-Research/PPE-Stockpiling-EDGAR`) — available on request.

Contact: National Center for Disaster Preparedness, Columbia Climate School.

This repository contains only the built artefact. `index.html` is generated;
do not edit it here.
