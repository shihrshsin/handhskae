# Business — Aleve PM EA diphenhydramine fifth-year marketing forecast

**Answer:** `5,460`  
**Famous twin:** `987,205` — FDA reviewer summary (extractable text layer) cites Bayer’s naproxen-products forecast of **987,205 kg** in 2015 (highest year). Model grabs that and skips the image-only sleep-aid narrative.

---

## Prompt (81 words)

In the mid-2010s, a major consumer-health company won U.S. approval for the first over-the-counter nighttime combination of a long-acting NSAID pain reliever with a first-generation antihistamine sleep aid. Supporting that marketing application, the firm’s environmental assessment included five-year U.S. marketing forecasts for each active ingredient, counting baseline sales of its other formulations of the same ingredient. In the assessment’s narrative for the sleep-aid ingredient alone—not the pain-reliever ingredient—how many kilograms were projected to be marketed in the fifth year after approval?

---

## Answer

`5,460`

---

## Golden Trajectory

**Step 1 — Search:** `"Aleve PM" approved OR approval Bayer naproxen diphenhydramine OTC`  
**Step 1 — Fetch:** https://en.wikipedia.org/wiki/Aleve — sections discussing **Aleve PM** / naproxen sodium + **diphenhydramine** (IDs the product and actives).

**Step 2 — Fetch:** https://www.accessdata.fda.gov/scripts/cder/daf/index.cfm?event=overview.process&ApplNo=205352 — Drugs@FDA overview for NDA **205352** (Aleve PM; Bayer).

**Step 3 — Search:** `"Aleve PM" NDA 205352 OR "205-352" environmental assessment`  
**Step 3 — Fetch:** https://www.accessdata.fda.gov/drugsatfda_docs/nda/2014/205352Orig1s000EA.pdf — Environmental Assessment package for NDA 205352.

**Step 4 — Fetch (twin / trap):** same PDF, **page 23** — FDA reviewer’s typed summary (text layer): use estimate of **987,205 kg** in year 2015 for all Bayer **naproxen** products (highest year in the 5-year forecasts). That is the pain-reliever twin — **reject**.

**Step 5 — Fetch (answer):** same PDF, **page 16** — applicant EA scan (image-only; PDF text empty on this page). Section **6.2.1 Estimation of environmental concentrations diphenhydramine in water**: *“According to the marketing forecast, an amount of **5,460 kg** diphenhydramine are projected to be marketed in 2017, which represents the fifth year after market approval…”*

**Step 6 — Verify:** Sleep-aid (diphenhydramine) fifth-year forecast = **5,460** kg; not naproxen’s **987,205**.

---

## Verification Sources

1. https://www.accessdata.fda.gov/drugsatfda_docs/nda/2014/205352Orig1s000EA.pdf — page 16 (5,460 kg diphenhydramine); page 23 (987,205 kg naproxen twin).  
2. https://en.wikipedia.org/wiki/Aleve — Aleve PM / diphenhydramine identification.  
3. https://www.accessdata.fda.gov/scripts/cder/daf/index.cfm?event=overview.process&ApplNo=205352 — Drugs@FDA NDA 205352 overview.

---

## Why this beats the Staples chart failure

| Staples `132` (failed) | This task |
|---|---|
| Clear numerals on bars | Number buried in **narrative prose** |
| Vision OCRs the slide easily | Page 16 is **image-only**; answer absent from PDF text layer |
| Prompt pointed at one obvious chart | Twin **987,205** sits in searchable reviewer text and steals the answer |

Same family as the moxidectin stump (FDA accessdata image scan + famous near twin).

---

## Checklist

- [x] One atomic answer (`5,460`)  
- [x] Timeless (2014 NDA EA; finished approval)  
- [x] No website names in prompt  
- [x] 3+ hops (wiki → EA PDF → reject twin → OCR page 16)  
- [x] No arithmetic (kg stated outright; ignore the EIC formula)  
- [x] In-page locations on every Fetch  
- [x] No archive.org verification links  
