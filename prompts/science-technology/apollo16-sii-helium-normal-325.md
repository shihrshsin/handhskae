# Science & Technology — Apollo 16 Saturn V S-II helium “normal” drop (Table 2)

**Answer:** `325`  
**Famous twin:** `890` — §6.2 body text (searchable OCR) states Engine No. 4 experienced an **890 psi** pressure drop; same page also gives a second temptation, nominal drop **approximately 400 psi**.  
**Why hard:** Table 2’s comparison baseline (**normal 325 psi**) is only in the **image-only** anomalies table (PDF page 31; printed roman **xxx**); `325 psi` never appears in the PDF text layer.

---

## Prompt (77 words)

In NASA’s 1972 Saturn V launch-vehicle flight evaluation report for the Apollo 16 mission (vehicle AS-511), the front-matter summary of significant anomalies includes a table entry for excessive J-2 Engine No. 4 helium consumption during S-II engine start. That entry compares the observed system pressure drop with a stated “normal” drop. Ignoring the later narrative’s “nominal” and observed-drop figures, what exact pressure drop in pounds per square inch does that anomalies-summary table cite as the normal value?

---

## Answer

`325`

---

## Golden Trajectory

**Step 1 — Search:** `Apollo 16 Saturn V AS-511 launch vehicle flight evaluation report NASA`

**Step 2 — Fetch:** https://en.wikipedia.org/wiki/Apollo_16 — **Launch vehicle** section: Saturn V designated **AS-511** (confirms mission/vehicle ID used in the report title).

**Step 3 — Fetch:** https://ntrs.nasa.gov/citations/19730025090 — NTRS record *Saturn 5 launch vehicle flight evaluation report-AS-511 Apollo 16 mission* (NASA-TM-X-69535 / MPR-SAT-FE-72-1; June 19, 1972).

**Step 4 — Verify:** Official NASA postflight launch-vehicle evaluation for Apollo 16 / AS-511.

**Step 5 — Filter:** Question is about the front-matter **Table 2. Summary of Significant Anomalies**, Item 1 (S-II/Propulsion), not the later §6.2 narrative alone.

**Step 6 — Fetch (twin / trap):** https://ntrs.nasa.gov/api/citations/19730025090/downloads/19730025090.pdf — **§6.2** (PDF page **75**): *“Nominal helium pressure drop during start is approximately **400 psi**. Engine number 4 experienced an **890 psi** pressure drop…”* — searchable OCR; reject as answers to the table’s “normal” wording.

**Step 7 — Fetch (answer):** same PDF — **Table 2. Summary of Significant Anomalies**, printed page **xxx**, **PDF page 31**. Table body is a **raster scan** (page text layer ≈ 82 characters of garbled title fragments only). Item 1 DESCRIPTION (CAUSE): *“J-2 Engine No. 4 helium consumption during engine start operations excessive. Pressure in system dropped 890 psi compared to normal **325** psi.”*

**Step 8 — Verify:** Table-cited normal drop = **325** psi. Whole-PDF text search finds **890 psi** and **400 psi** but **no** `325 psi`.

**Step 9 — Twin:** Search hits **890** (and **400**); **325** is recoverable only by reading the image-only Table 2 cell.

---

## Verification Sources

1. https://en.wikipedia.org/wiki/Apollo_16 — Launch vehicle section (AS-511).  
2. https://ntrs.nasa.gov/citations/19730025090 — NTRS citation for NASA-TM-X-69535 / AS-511 Apollo 16 flight evaluation.  
3. https://ntrs.nasa.gov/api/citations/19730025090/downloads/19730025090.pdf — PDF page 31 / printed xxx, Table 2 Item 1 (**325**); PDF page 75, §6.2 twins (**890**, **400**).

---

## Failure justification (expected)

Models that rely on full-text search or §6.2 OCR will answer **890** (observed drop) or **400** (body “nominal”), missing the anomalies table’s image-only **normal 325**. The value **325 psi** is absent from the PDF text layer.

---

## Checklist

- [x] One atomic answer (`325`)  
- [x] Timeless (1972 NASA TM)  
- [x] No website names in prompt  
- [x] 3+ hops  
- [x] No arithmetic  
- [x] In-page locations on every Fetch  
- [x] No archive.org verification links  
- [x] GT ↔ Verification Sources URL parity  
- [x] Image-only answer + searchable twin(s)  
