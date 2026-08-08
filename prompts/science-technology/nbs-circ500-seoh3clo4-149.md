# Science & Technology — NBS Circular 500 Se(OH)₃ClO₄ ΔHf° (−149.0)

**Answer:** `-149.0`  
**Famous twin:** `33.14` / `33.61` — adjacent Table 15-2 **Se₂(g)** heats of formation sit in the PDF **text layer** (OCR); models that grep the circular latch onto these.  
**Same-page traps:** H₂SeO₄(aq, ∞) **−145.3**; SeO₂·SO₃(c) **−167.1**; SeF₆(g) **−246.**  
**Why hard / deeper than Apollo 16:** 1952 NBS Circ 500 Table 15-3 cell is **image-only** (PDF page 56 text layer = 5 chars). Value **−149.0** is absent from the whole-PDF text layer and is **not** quoted on Scribd/secondary web (unlike Apollo table text and unlike Se(g) +48.37).

---

## Prompt (74 words)

In 1952 the National Bureau of Standards issued its big circular of selected chemical thermodynamic properties—the Series I tables chemists still nickname by that circular’s number. Buried in the selenium section is a row for the crystalline complex written Se(OH)₃ClO₄, not the gaseous dimer and not the oxyacids around it. For that crystalline solid alone, what standard heat of formation at 298.16 K does the table report, in kilocalories per mole, exactly as printed?

---

## Answer

`-149.0`

---

## Golden Trajectory

**Step 1 — Search:** `"Circular 500" "Selected Values of Chemical Thermodynamic Properties" Rossini NBS`

**Step 2 — Fetch:** https://nvlpubs.nist.gov/nistpubs/sp958-lide/html/093-096.html — NIST historical essay: identifies Rossini et al. *Selected Values of Chemical Thermodynamic Properties* as **“Circular 500”** (1952 Series I tables).

**Step 3 — Fetch:** https://www.nist.gov/publications/circular-bureau-standards-no-500selected-values-chemical-thermodynamic-properties — NIST publications record for NBS CIRC 500 (Rossini, Wagman, Evans, Levine, Jaffe; 1952); links the official PDF / DOI.

**Step 4 — Verify:** Document is NBS Circular 500 (1952), Series I thermodynamic tables.

**Step 5 — Filter:** Question is the selenium Series I table entry for crystalline **Se(OH)₃ClO₄** ΔHf° at **298.16 K**, not Se₂(g) and not other Se oxy/halogen rows.

**Step 6 — Fetch (twin / trap):** https://nvlpubs.nist.gov/nistpubs/Legacy/circ/nbscircular500.pdf — **Table 15-2** Selenium, printed page **47**, **PDF page 55**. Textable OCR includes **Se₂** ΔHf° = **33.61** (0 K) and **33.14** (298.16 K) kcal/mole — reject.

**Step 7 — Fetch (answer):** same PDF — **Table 15-3** Selenium, printed page **48**, **PDF page 56**. Page text layer is essentially blank (**~5 characters**). Row **Se(OH)₃ClO₄** / state **c**: ΔHf° at 298.16 K = **−149.0** kcal/mole (raster table cell).

**Step 8 — Verify:** Whole-PDF text search finds **33.14** / **33.61** and does **not** find **−149.0**. Answer = **−149.0**.

**Step 9 — Twin:** Search hits Se₂ **33.14/33.61**; **−149.0** is only on the image-only Table 15-3 page.

---

## Verification Sources

1. https://nvlpubs.nist.gov/nistpubs/sp958-lide/html/093-096.html — NIST essay identifying Circular 500 / *Selected Values*.  
2. https://www.nist.gov/publications/circular-bureau-standards-no-500selected-values-chemical-thermodynamic-properties — NIST pub record for NBS CIRC 500 (1952).  
3. https://nvlpubs.nist.gov/nistpubs/Legacy/circ/nbscircular500.pdf — PDF page 56 / printed 48, Table 15-3 Se(OH)₃ClO₄(c) **−149.0**; PDF page 55 / printed 47, Table 15-2 Se₂ twin **33.14** / **33.61**.

---

## Failure justification (expected)

Text-searching the circular surfaces the Se₂ twins (**33.14** / **33.61**) and misses **−149.0**, which has no text layer and no Scribd/web OCR mirror. Same-page misreads of H₂SeO₄(∞) **−145.3** or SeO₂·SO₃ **−167.1** are plausible distractors. Replaces Apollo 16 **325 psi**, which failed because Scribd already OCR’d that anomalies table.

---

## Checklist

- [x] One atomic answer (`-149.0`)  
- [x] Timeless (1952 NBS Circ 500)  
- [x] No website names in prompt  
- [x] 3+ hops  
- [x] No arithmetic  
- [x] In-page locations on every Fetch  
- [x] No archive.org verification links  
- [x] GT ↔ Verification Sources URL parity  
- [x] Image-only answer + searchable twin  
- [x] Deeper than Apollo; answer pairing not web-mirrored  
