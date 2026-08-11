# Legal — Glen Canyon Dam 1995 FEIS camping-beach table total

**Answer:** `239`  
**Famous twins:** `226` (suitable beaches after decline); `333` (1975 inventory). Secondary traps: `37` (low-water-only add-ons); `276` (=239+37).  
**Observed model failure:** Answered `226`.  
**Doc note:** Same 1995 Glen Canyon Dam operations FEIS (usbr.gov Chapter 3) can seed more Legal stumps — raster figures/tables with prose twins on adjacent pages (e.g. Fig. III-36 pies, Fig. III-37 inundation bars already used as `18%`).

---

## Prompt (95 words)

In the Bureau of Reclamation’s 1995 final environmental impact statement on the operation of Glen Canyon Dam—whose preferred alternative was the Modified Low Fluctuating Flow Alternative—the recreation analysis cites a 1975 inventory of about 333 campsites in the river corridor and later states that suitable camping beaches above the new high-water zone had declined to 226 sites. On the reach-by-reach distribution table of camping beaches by size class (small, medium, and large), excluding the parenthetical counts of additional beaches available only at low water, what grand total number of camping beaches does that table report?

---

## Answer

`239`

---

## Golden Trajectory

**Step 1 — Search:** `"Operation of Glen Canyon Dam" "Final Environmental Impact Statement" 1995 "Modified Low Fluctuating Flow"`  
**Step 1 — Fetch:** https://en.wikipedia.org/wiki/Glen_Canyon_Dam — Environmental issues section points to the 1995 federal operations EIS. Good for document ID only; no preferred-alternative name and no table total.  
**Step 1 — Verify:** Right FEIS family (Reclamation, Glen Canyon Dam operations, 1995).  
**Step 1 — Filter:** Stay on that FEIS’s recreation / camping-beach material — skip tourism blurbs and later park pages.

**Step 2 — Fetch:** https://www.usbr.gov/uc/envdocs/eis/gc/gcdOpsFEIS.html — Reclamation’s chapter-by-chapter host for the March 1995 *Operation of Glen Canyon Dam* Final EIS. Cover/Summary and Chapter 3 are both linked here.  
**Step 2 — Verify:** Lead-agency copy, not a blog rewrite.  
**Step 2 — Filter:** Pull PDFs from this index.

**Step 3 — Fetch:** https://www.usbr.gov/uc/envdocs/eis/gc/pdfs/Cov-con/cov-con.pdf — Cover/Summary names the preferred alternative: **Modified Low Fluctuating Flow Alternative**.  
**Step 3 — Verify:** Matches the prompt’s MLFF constraint.  
**Step 3 — Filter:** Correct FEIS / correct preferred alternative before opening Chapter 3.

**Step 4 — Fetch (twins):** https://www.usbr.gov/uc/envdocs/eis/gc/pdfs/Ch3/chap3-1.pdf — Chapter 3, printed page **156**. Selectable prose: about **333** campsites in the 1975 inventory; suitable beaches above the new high-water zone down to **226** sites (48 percent decline).  
**Step 4 — Verify:** Those are the prompt’s twin figures, in body text.  
**Step 4 — Filter:** **333** and **226** are inventory / decline sentences — not the size-class table’s grand total.

**Step 5 — Fetch (answer):** same Chapter 3 PDF, printed page **158** (Chapter PDF page **93**) — **Table III-13**, “Distribution of camping beaches by reach” (Kearsley and Warren, 1992). Full raster page, no usable text layer. Totals row: Small **47**, Medium **102**, Large **90**, grand total **239 (37)**. Note: parentheses = extra beaches only at low water (15,000 cfs or less).  
**Step 5 — Verify:** Drop the parenthetical **37**; table grand total is **239**.  
**Step 5 — Filter:** Lock **239**. Dump **226**, **333**, **37**, and **276** (239+37).

**Step 6 — Fetch (mirror check):** http://www.riversimulator.org/Resources/USBR/LTEP/1995EIS.pdf — same FEIS in one file. Text search finds **226** and **333**; it does not find **239**, because Table III-13 sits on a zero-text scan (printed p.158 / full PDF ~p.180).  
**Step 6 — Verify:** Answer is image-only; twins are what search surfaces.  
**Step 6 — Filter:** Keep **239**.

---

## Verification Sources

1. https://en.wikipedia.org/wiki/Glen_Canyon_Dam — 1995 operations FEIS exists.  
2. https://www.usbr.gov/uc/envdocs/eis/gc/gcdOpsFEIS.html — official FEIS chapter index.  
3. https://www.usbr.gov/uc/envdocs/eis/gc/pdfs/Cov-con/cov-con.pdf — Modified Low Fluctuating Flow preferred alternative.  
4. https://www.usbr.gov/uc/envdocs/eis/gc/pdfs/Ch3/chap3-1.pdf — p.156 twins **333** / **226**; p.158 Table III-13 = **239** (exclude parenthetical **37**).  
5. http://www.riversimulator.org/Resources/USBR/LTEP/1995EIS.pdf — full mirror; search hits **226**/**333**, not **239**.

---

## Failure justification

The model answered **226**, which is the suitable-beach decline figure in Chapter 3 prose on printed page 156 — the same number the prompt uses as bait. It never opened the zero-text Table III-13 page (printed p.158), where the size-class grand total is **239** once the low-water parenthetical **37** is excluded. So it treated a nearby narrative twin as the table total.

---

## Checklist

- [x] One atomic answer (`239`)  
- [x] Timeless (1995 FEIS)  
- [x] No website names in prompt  
- [x] Official usbr.gov host  
- [x] No self-authored verification pages  
- [x] Answer only on raster table; twins in searchable text  
- [x] Observed fail = twin (`226`)  
- [x] GT ↔ Verification Sources URL parity  
- [x] Distinct from beach-inundation `18%` bar-chart stump  
