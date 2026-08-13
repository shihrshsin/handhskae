# Legal - Glen Canyon Dam 1995 FEIS Fig. III-36 Non-Critical Overgrown slice

**Answer:** `4%`  
**Famous twin:** `nearly 50 percent` / `50%` - same-page body text on vegetation encroachment in wider noncritical reaches.  
**Secondary traps:** Non-Critical **47%** (Eroded); **27%** (Other); **22%** (Eroded/Overgrown); Critical **15%** (Overgrown).  
**Observed model failure:** Answered `47%` (took the Non-Critical **Eroded** slice / secondary-paper conflation as Overgrown; also leaned on the nearly-50% twin).  
**Doc:** Same 1995 Glen Canyon Dam operations FEIS Chapter 3 / Figure III-36 as the Non-Critical Eroded `47%` and Eroded/Overgrown `22%` stumps - different pie slice (Overgrown alone).

---

## Prompt (62 words)

In the 1995 final environmental impact statement on the operation of Glen Canyon Dam whose preferred alternative was the Modified Low Fluctuating Flow Alternative, the text notes that vegetation encroachment accounted for nearly 50 percent of campsite degradation in wider noncritical reaches. What exact percentage does the Non-Critical Reaches pie in the figure those sentences cite assign to the Overgrown category alone?

---

## Answer

`4%`

---

## Golden Trajectory

**Step 1 - Search:** `"Operation of Glen Canyon Dam" "Final Environmental Impact Statement" 1995 "Modified Low Fluctuating Flow"`  
**Step 1 - Fetch:** https://en.wikipedia.org/wiki/Glen_Canyon_Dam - Environmental issues section cites the 1995 federal operations EIS. Document ID only; no preferred-alternative name and no pie percentages.  
**Step 1 - Verify:** Right FEIS family (prompt does not name the lead agency).  
**Step 1 - Filter:** Identify Reclamation as author; stay on campsite-degradation material.

**Step 2 - Fetch:** https://www.usbr.gov/uc/envdocs/eis/gc/gcdOpsFEIS.html - Reclamation's chapter-by-chapter host for the March 1995 *Operation of Glen Canyon Dam* Final EIS. Links Cover/Summary and Chapter 3.  
**Step 2 - Verify:** Lead-agency copy (prompt never said "Bureau of Reclamation" or "recreation chapter").  
**Step 2 - Filter:** Pull PDFs from this index.

**Step 3 - Fetch:** https://www.usbr.gov/uc/envdocs/eis/gc/pdfs/Cov-con/cov-con.pdf - Cover/Summary. Preferred alternative is the **Modified Low Fluctuating Flow Alternative**.  
**Step 3 - Verify:** Matches the prompt's MLFF constraint.  
**Step 3 - Filter:** Correct FEIS / correct preferred alternative before Chapter 3.

**Step 4 - Fetch (twin):** https://www.usbr.gov/uc/envdocs/eis/gc/pdfs/Ch3/chap3-1.pdf - Chapter 3, printed page **156**. Selectable prose: encroachment accounted for nearly **50** percent of the campsite degradation in wider (noncritical) reaches (**figure III-36**).  
**Step 4 - Verify:** Narrative twin is "nearly 50 percent"; figure callout is what the prompt requires the solver to identify.  
**Step 4 - Filter:** Reject **50%** / "nearly 50 percent" as the Non-Critical **Overgrown** slice. Overgrown alone is not the encroachment narrative total.

**Step 5 - Fetch (answer):** same Chapter 3 PDF, printed page **156** - **Figure III-36**, "Number of camps degraded by reach type and type of degradation." Two raster pies. Non-Critical Reaches: Eroded **47% (91)**; **Overgrown 4% (8)**; Other **27% (52)**; Eroded/Overgrown **22% (44)**. Critical: Eroded **71% (29)**; Overgrown **15% (6)**; Other **7% (3)**; Eroded/Overgrown **7% (3)**. Pie numerals are image-only (no Non-Critical Overgrown `4%` in the Chapter 3 text layer).  
**Step 5 - Verify:** Non-Critical **Overgrown** slice is **4%**.  
**Step 5 - Filter:** Lock **4%**. Dump **50%**, Non-Critical **47% / 27% / 22%**, and Critical Overgrown **15%**.

**Step 6 - Fetch (mirror check):** http://www.riversimulator.org/Resources/USBR/LTEP/1995EIS.pdf - full-bound FEIS. Text search finds the "nearly 50 percent" line and does not surface Figure III-36's Non-Critical **Overgrown 4%** as a recreation pie label (pie is raster).  
**Step 6 - Verify:** Answer is chart-image-only; twin is what search surfaces next to the figure callout.  
**Step 6 - Filter:** Keep **4%**.

---

## Verification Sources

1. https://en.wikipedia.org/wiki/Glen_Canyon_Dam - 1995 operations FEIS exists.  
2. https://www.usbr.gov/uc/envdocs/eis/gc/gcdOpsFEIS.html - official FEIS chapter index.  
3. https://www.usbr.gov/uc/envdocs/eis/gc/pdfs/Cov-con/cov-con.pdf - Modified Low Fluctuating Flow preferred alternative.  
4. https://www.usbr.gov/uc/envdocs/eis/gc/pdfs/Ch3/chap3-1.pdf - printed p.156 twin "nearly 50 percent"; Figure III-36 Non-Critical **Overgrown = 4%**.  
5. http://www.riversimulator.org/Resources/USBR/LTEP/1995EIS.pdf - full mirror; prose twin searchable; pie slice image-only.

---

## Failure justification

The model answered **47%**, after web search. Figure III-36's Non-Critical **Overgrown** slice is **4% (8)**, not 47%. **47%** is the Non-Critical **Eroded** slice on the same pie. The model also leaned on a secondary campsite paper and treated the prompt's nearly-**50%** vegetation-encroachment twin as if it named the Overgrown-alone percentage. So it never recovered the true Overgrown label from the raster pie.

---

## Checklist

- [x] One atomic answer (`4%`)  
- [x] Timeless (1995 FEIS)  
- [x] No website names in prompt  
- [x] Official usbr.gov host  
- [x] No self-authored verification pages  
- [x] Answer only on raster chart; twins in searchable text  
- [x] Observed fail = wrong slice / twin (`47%` ≠ `4%`)  
- [x] GT ↔ Verification Sources URL parity  
- [x] No em dashes  
- [x] Lean discovery: no agency / chapter / figure-number spoon-feeding  
- [x] Distinct from Non-Critical Eroded `47%` and Eroded/Overgrown `22%` on the same figure  
