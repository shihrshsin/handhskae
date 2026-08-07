# Business — Aleve PM FDA EA: fifth-year diphenhydramine marketing forecast

**Answer:** `5,460 kg`  
**Famous twin:** `987,205 kg` — Bayer’s U.S. naproxen marketing-forecast figure quoted in the *extractable* FDA reviewer summary (and in search snippets for this same PDF). Models that stop at the text layer / Google hit substitute the naproxen twin for the sleep-aid ingredient.

---

## Prompt (118 words)

In the mid-2010s, a major consumer-health company won U.S. approval for the first over-the-counter nighttime combination of a long-acting NSAID pain reliever with a first-generation antihistamine sleep aid. Supporting that marketing application, the firm’s environmental assessment included five-year U.S. marketing forecasts for each active ingredient, counting baseline sales of its other formulations of the same ingredient. In the assessment’s narrative for the sleep-aid ingredient alone—not the pain-reliever ingredient—how many kilograms were projected to be marketed in the fifth year after approval?

---

## Answer

`5,460 kg` (also acceptable: `5460 kg`, `5,460 kilograms`)

---

## Golden Trajectory

**Step 1 — Search:** `"Aleve PM" FDA approval` OR `naproxen diphenhydramine NDA`  
**Step 1 — Fetch:** https://en.wikipedia.org/wiki/Aleve_PM (or https://en.wikipedia.org/wiki/Naproxen/diphenhydramine) — identifies Aleve PM / naproxen–diphenhydramine, Bayer, OTC dual product. No kilogram forecast on Wikipedia.

**Step 2 — Search:** `"Aleve PM" NDA` OR `NDA 205352` environmental assessment  
**Step 2 — Fetch:** https://www.accessdata.fda.gov/drugsatfda_docs/nda/2014/205352Orig1s000TOC.cfm — NDA 205352 review package TOC.

**Step 3 — Fetch:** https://www.accessdata.fda.gov/drugsatfda_docs/nda/2014/205352Orig1s000EA.pdf — Environmental Assessment / FONSI package.

**Step 4 — Calibrate (twin trap):** PDF text layer / FDA reviewer executive summary states naproxen use estimate **987,205 kg** (highest year in the 5-year marketing forecasts). Search engines surface this twin; `pdftotext` extracts it. Diphenhydramine kilograms are **absent** from the text layer.

**Step 5 — Read image pages:** Applicant EA body is image-only (pages ~3–21). On **PDF page 16**, section 6.2.1 narrative: *“According to the marketing forecast, an amount of 5,460 kg diphenhydramine are projected to be marketed in 2017…”*

**Step 6 — Verify:** Answer is **5,460 kg** (diphenhydramine), not twin **987,205 kg** (naproxen).

---

## Verification Sources

1. https://www.accessdata.fda.gov/drugsatfda_docs/nda/2014/205352Orig1s000EA.pdf — page **16** (applicant EA image scan); paragraph quote below.  
2. Same PDF, FDA reviewer summary (~pages 22–23) — extractable twin `987,205 kg` naproxen.  
3. https://en.wikipedia.org/wiki/Aleve_PM — product ID only; no kg forecast.

---

## Paragraph quote (source)

> According to the marketing forecast, an amount of 5,460 kg diphenhydramine are projected to be marketed in 2017, which represents the fifth year after market approval of the NDA and includes baseline sales of other diphenhydramine formulations (see Annex, CBI).

---

## pdftotext proof

| Check | Result |
|---|---|
| `pdftotext` whole PDF for `5,460` / `5460` | **No matches** |
| `pdftotext -f 16 -l 16` char count | **1** (image-only page) |
| `pdftotext` whole PDF for `987,205` | **Match** in FDA reviewer summary |
| Answer in Wikipedia / easy news | **No** (wiki has no kg forecast; news covers launch/dose only) |

---

## Why this follows the moxidectin pattern (not Staples chart-OCR)

| Pattern piece | Here |
|---|---|
| Atomic answer in narrative prose | Marketing-forecast sentence in EA §6.2.1 — not a labeled bar/pie |
| Image-only / hard extract | Applicant EA pages image-scanned; answer invisible to `pdftotext` |
| Famous twin in same package | **987,205 kg** naproxen in searchable FDA summary / SERP snippets |
| No clear “commercial sales” heading jump | Nested under environmental-concentration estimation for diphenhydramine |
| Not chart-reading | No printed numeral on a bar; vision must read buried prose |
| Business metric | Fifth-year projected commercial marketing volume (kg API) |

---

## Web-check results

- `"5,460 kg" / "5460 kg" diphenhydramine OR Aleve PM`: **no** hits tying the figure to this forecast (unrelated industrial weights only).  
- `"987,205" naproxen / Aleve EA`: **surfaces** the FDA EA reviewer summary (twin).  
- Wikipedia Aleve PM / Naproxen/diphenhydramine: product facts only; **no** kilogram marketing forecast.

---

## Checklist

- [x] One atomic answer (`5,460 kg`)  
- [x] Timeless (2014 NDA package; finished)  
- [x] No website names in prompt  
- [x] 3+ hops (wiki → NDA TOC → EA PDF → image page 16)  
- [x] No arithmetic  
- [x] Not a bar/pie chart numeral  
- [x] Not Illumina $315M / Staples 132  
- [x] No archive.org verification links  
