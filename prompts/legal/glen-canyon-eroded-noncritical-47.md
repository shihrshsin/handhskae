# Legal — Glen Canyon Dam 1995 FEIS Fig. III-36 Non-Critical Eroded slice

**Answer:** `47%`  
**Famous twin:** `nearly 50 percent` / `50%` — same-page body text on vegetation encroachment in wider noncritical reaches.  
**Secondary traps:** Non-Critical **27%** (Other); **22%** (Eroded/Overgrown); **4%** (Overgrown); Critical **71%** (Eroded).  
**Observed model failure:** Answered `27%` (misread the Non-Critical **Other** slice as **Eroded**; also leaned on a CiteSeerX secondary paper).  
**Doc:** Same 1995 Glen Canyon Dam operations FEIS Chapter 3 as the `239` table stump and the `18%` inundation bar stump — different figure (pie, not table/bar).

---

## Prompt (96 words)

In the Bureau of Reclamation’s 1995 final environmental impact statement on the operation of Glen Canyon Dam—whose preferred alternative was the Modified Low Fluctuating Flow Alternative—the recreation chapter includes a two-pie figure on the number of camps degraded by reach type and type of degradation. Setting aside the body-text remark that vegetation encroachment accounted for nearly 50 percent of campsite degradation in wider noncritical reaches, what exact percentage does the Non-Critical Reaches pie assign to the Eroded category?

---

## Answer

`47%`

---

## Golden Trajectory

**Step 1 — Search:** `"Operation of Glen Canyon Dam" "Final Environmental Impact Statement" 1995 "Modified Low Fluctuating Flow"`  
**Step 1 — Fetch:** https://en.wikipedia.org/wiki/Glen_Canyon_Dam — Environmental issues section cites the 1995 federal operations EIS. Document ID only; no preferred-alternative name and no pie percentages.  
**Step 1 — Verify:** Right FEIS family.  
**Step 1 — Filter:** Stay on that FEIS’s recreation / campsite-degradation material.

**Step 2 — Fetch:** https://www.usbr.gov/uc/envdocs/eis/gc/gcdOpsFEIS.html — Reclamation’s chapter-by-chapter host for the March 1995 *Operation of Glen Canyon Dam* Final EIS. Links Cover/Summary and Chapter 3.  
**Step 2 — Verify:** Lead-agency copy.  
**Step 2 — Filter:** Pull PDFs from this index.

**Step 3 — Fetch:** https://www.usbr.gov/uc/envdocs/eis/gc/pdfs/Cov-con/cov-con.pdf — Cover/Summary. Preferred alternative is the **Modified Low Fluctuating Flow Alternative**.  
**Step 3 — Verify:** Matches the prompt’s MLFF constraint.  
**Step 3 — Filter:** Correct FEIS / correct preferred alternative before Chapter 3.

**Step 4 — Fetch (twin):** https://www.usbr.gov/uc/envdocs/eis/gc/pdfs/Ch3/chap3-1.pdf — Chapter 3, printed page **156**. Selectable prose: *“encroachment accounted for nearly **50** percent of the campsite degradation in wider (noncritical) reaches (figure III-36).”*  
**Step 4 — Verify:** That is the prompt’s twin — narrative “nearly 50 percent,” not a pie-slice label.  
**Step 4 — Filter:** Reject **50%** / “nearly 50 percent” as the exact Non-Critical **Eroded** slice.

**Step 5 — Fetch (answer):** same Chapter 3 PDF, printed page **156** — **Figure III-36**, “Number of camps degraded by reach type and type of degradation.” Two raster pies (Critical / Non-Critical). Non-Critical Reaches labels: **Eroded 47% (91)**; Overgrown **4% (8)**; Other **27% (52)**; Eroded/Overgrown **22% (44)**. Critical Reaches: Eroded **71% (29)**; Overgrown **15% (6)**; Other **7% (3)**; Eroded/Overgrown **7% (3)**. Pie numerals are image-only (no `47%` in the Chapter 3 text layer).  
**Step 5 — Verify:** Non-Critical **Eroded** slice is **47%**.  
**Step 5 — Filter:** Lock **47%**. Dump **50%**, Critical **71%**, and the other Non-Critical slices (**4% / 27% / 22%**).

**Step 6 — Fetch (mirror check):** http://www.riversimulator.org/Resources/USBR/LTEP/1995EIS.pdf — full-bound FEIS. Text search finds the “nearly 50 percent” line and does not surface Figure III-36’s Non-Critical **Eroded 47%** as a recreation pie label (pie is raster; other unrelated “47 percent” hits elsewhere in the bound volume are not this slice).  
**Step 6 — Verify:** Answer is chart-image-only; twin is what search surfaces next to the figure callout.  
**Step 6 — Filter:** Keep **47%**.

---

## Verification Sources

1. https://en.wikipedia.org/wiki/Glen_Canyon_Dam — 1995 operations FEIS exists.  
2. https://www.usbr.gov/uc/envdocs/eis/gc/gcdOpsFEIS.html — official FEIS chapter index.  
3. https://www.usbr.gov/uc/envdocs/eis/gc/pdfs/Cov-con/cov-con.pdf — Modified Low Fluctuating Flow preferred alternative.  
4. https://www.usbr.gov/uc/envdocs/eis/gc/pdfs/Ch3/chap3-1.pdf — printed p.156: twin “nearly 50 percent”; Figure III-36 Non-Critical **Eroded = 47%**.  
5. http://www.riversimulator.org/Resources/USBR/LTEP/1995EIS.pdf — full mirror; prose twin searchable; pie slice image-only.

---

## Failure justification

The model answered **27%**, which is the Non-Critical Reaches **Other** slice on Figure III-36 — not **Eroded**. The Non-Critical **Eroded** slice is **47% (91)**. It also leaned on a CiteSeerX secondary paper and swapped categories (claiming 27% eroded / 47% overgrown), which does not match the FEIS pie labels (Eroded 47%, Overgrown 4%, Other 27%, Eroded/Overgrown 22%). So it misread the raster legend instead of reporting the Non-Critical **Eroded** percentage.

---

## Checklist

- [x] One atomic answer (`47%`)  
- [x] Timeless (1995 FEIS)  
- [x] No website names in prompt  
- [x] Official usbr.gov host  
- [x] No self-authored verification pages  
- [x] Answer on raster pie; twin in searchable prose  
- [x] Distinct from `239` table and `18%` inundation bar  
- [x] GT ↔ Verification Sources URL parity  
