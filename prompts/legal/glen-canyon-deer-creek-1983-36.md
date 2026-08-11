# Legal — Glen Canyon Dam 1995 FEIS Fig. III-38 Deer Creek 1983

**Answer:** `3.6`  
**Famous twins:** `2.3` (Deer Creek sites per mile in body text — the 1991 chart bar); `1.0` (corridor-wide average in the same sentence).  
**Secondary traps:** `1.1` / `0.7` (1991 Non-critical / Critical); `2.2` (1973 Deer Creek); `2.7` / `1.9` (1983 Non-critical / Total).  
**Observed model failure:** Answered `3.1` (OCR/misread of the raster **3.6** Deer Creek 1983 bar on Figure III-38; correctly found the FEIS / figure callout and the prose twin **2.3** for 1991).  
**Doc:** Same 1995 Glen Canyon Dam operations FEIS Chapter 3 as the `18%` / `239` / `47%` recreation stumps — different figure (campsites-per-mile bars, not inundation / size-class table / degradation pies).

---

## Prompt (85 words)

In the Bureau of Reclamation’s 1995 final environmental impact statement on the operation of Glen Canyon Dam—whose preferred alternative was the Modified Low Fluctuating Flow Alternative—the recreation chapter states that campsites average 1.0 per mile overall and that the Deer Creek reach has more sites per mile than any other reach at 2.3. On the accompanying bar chart of average campsites per mile by reach type for 1973, 1983, and 1991, what exact average campsites-per-mile value is shown for the Deer Creek reach in 1983?

---

## Answer

`3.6`

---

## Golden Trajectory

**Step 1 — Search:** `"Operation of Glen Canyon Dam" "Final Environmental Impact Statement" 1995 "Modified Low Fluctuating Flow"`  
**Step 1 — Fetch:** https://en.wikipedia.org/wiki/Glen_Canyon_Dam — Environmental issues section cites the 1995 federal operations EIS. Document ID only; no preferred-alternative name and no campsites-per-mile chart values.  
**Step 1 — Verify:** Right FEIS family.  
**Step 1 — Filter:** Stay on that FEIS’s recreation / camping-beach material.

**Step 2 — Fetch:** https://www.usbr.gov/uc/envdocs/eis/gc/gcdOpsFEIS.html — Reclamation’s chapter-by-chapter host for the March 1995 *Operation of Glen Canyon Dam* Final EIS. Links Cover/Summary and Chapter 3.  
**Step 2 — Verify:** Lead-agency copy.  
**Step 2 — Filter:** Pull PDFs from this index.

**Step 3 — Fetch:** https://www.usbr.gov/uc/envdocs/eis/gc/pdfs/Cov-con/cov-con.pdf — Cover/Summary. Preferred alternative is the **Modified Low Fluctuating Flow Alternative**.  
**Step 3 — Verify:** Matches the prompt’s MLFF constraint.  
**Step 3 — Filter:** Correct FEIS / correct preferred alternative before Chapter 3.

**Step 4 — Fetch (twins):** https://www.usbr.gov/uc/envdocs/eis/gc/pdfs/Ch3/chap3-1.pdf — Chapter 3, printed page **157**. Selectable prose: campsites average **1.0** per mile; critical **0.7** / noncritical **1.1**; Deer Creek reach **2.3** sites per mile; callout to figure III-38.  
**Step 4 — Verify:** Those are the prompt’s twin figures — the 1991-era narrative values, not the 1983 Deer Creek bar.  
**Step 4 — Filter:** Reject **2.3** and **1.0** as the 1983 Deer Creek chart value.

**Step 5 — Fetch (answer):** same Chapter 3 PDF, printed page **158** (Chapter PDF page **93**) — **Figure III-38**, “Number of campsites per mile by type of reach, 1973, 1983, and 1991” (modified from Kearsley and Warren, 1993). Full page is a zero-text raster scan. Deer Creek (stippled) bars: **1973 = 2.2**; **1983 = 3.6**; **1991 = 2.3**. Footnote: *1983 does not include “small” camps.  
**Step 5 — Verify:** 1983 Deer Creek bar label is **3.6**.  
**Step 5 — Filter:** Lock **3.6**. Dump **2.3**, **1.0**, **2.2**, and the other 1983 bars (**0.9** Critical / **2.7** Non-critical / **1.9** Total).

**Step 6 — Fetch (mirror check):** http://www.riversimulator.org/Resources/USBR/LTEP/1995EIS.pdf — full-bound FEIS. Text search finds the **1.0** / **2.3** prose on printed p.157 and does not surface Figure III-38’s Deer Creek **3.6** as a selectable recreation chart label (figure sits on the zero-text p.158 scan).  
**Step 6 — Verify:** Answer is chart-image-only; twins are what search surfaces next to the figure callout.  
**Step 6 — Filter:** Keep **3.6**.

---

## Verification Sources

1. https://en.wikipedia.org/wiki/Glen_Canyon_Dam — 1995 operations FEIS exists.  
2. https://www.usbr.gov/uc/envdocs/eis/gc/gcdOpsFEIS.html — official FEIS chapter index.  
3. https://www.usbr.gov/uc/envdocs/eis/gc/pdfs/Cov-con/cov-con.pdf — Modified Low Fluctuating Flow preferred alternative.  
4. https://www.usbr.gov/uc/envdocs/eis/gc/pdfs/Ch3/chap3-1.pdf — printed p.157 twins **1.0** / **2.3**; printed p.158 Figure III-38 Deer Creek **1983 = 3.6**.  
5. http://www.riversimulator.org/Resources/USBR/LTEP/1995EIS.pdf — full mirror; prose twins searchable; 1983 Deer Creek bar image-only.

---

## Failure justification

*(Fill after live ChatGPT web-browsing run.)*

---

## Checklist

- [x] One atomic answer (`3.6`)  
- [x] Timeless (1995 FEIS)  
- [x] No website names in prompt  
- [x] Official usbr.gov host  
- [x] No self-authored verification pages  
- [x] Answer only on raster chart; twins in searchable text  
- [ ] Observed fail recorded  
- [x] GT ↔ Verification Sources URL parity  
- [x] Distinct from `18%` / `239` / `47%` stumps from the same chapter  
