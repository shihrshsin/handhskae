# Legal - Glen Canyon Dam 1995 FEIS Fig. III-36 Critical Overgrown slice

**Answer:** `15%`  
**Famous twin:** `nearly 50 percent` / `50%` - same-page body text on vegetation encroachment in wider noncritical reaches.  
**Secondary traps:** Critical **71%** (Eroded); **7%** (Other); **7%** (Eroded/Overgrown); Non-Critical **4%** (Overgrown).  
**Observed model failure:** Answered `17%` (OCR/near-miss of Critical Overgrown **15% (6)**; also leaned on a secondary paper and swapped Non-Critical categories).  
**Doc:** Same 1995 Glen Canyon Dam operations FEIS Chapter 3 / Figure III-36 as the Non-Critical `47%` / `22%` / `4%` / `27%` stumps - Critical pie, Overgrown slice.

---

## Prompt (83 words)

In the 1995 final environmental impact statement on the operation of Glen Canyon Dam whose preferred alternative was the Modified Low Fluctuating Flow Alternative, the text states that in narrow critical reaches erosion was the primary cause of campsite degradation, while vegetation encroachment accounted for nearly 50 percent of campsite degradation in wider noncritical reaches. Setting aside that nearly-50-percent remark and the Non-Critical pie, what exact percentage does the Critical Reaches pie in the figure those sentences cite assign to the Overgrown category?

---

## Answer

`15%`

---

## Golden Trajectory

**Step 1 - Search:** `"Operation of Glen Canyon Dam" "Final Environmental Impact Statement" 1995 "Modified Low Fluctuating Flow"`  
**Step 1 - Fetch:** https://en.wikipedia.org/wiki/Glen_Canyon_Dam - Exact on-page clues (not a paraphrase): (a) body text: *"The EIS completed March 21, 1995 cemented some restrictions on dam operations..."*; (b) References footnote for that EIS discussion (cite note for the 1995 Reclamation book): *U.S. Bureau of Reclamation (1995). Operation of Glen Canyon Dam: Colorado River Storage Project, Arizona: final environmental impact statement*; (c) External links entry titled **"1995 Glen Canyon EIS"** pointing to https://www.usbr.gov/uc/envdocs/eis/gc/gcdOpsFEIS.html. Document ID / host only; no preferred-alternative name and no pie percentages.  
**Step 1 - Verify:** The page names the **1995** *Operation of Glen Canyon Dam* Final EIS and the Reclamation host (prompt does not name the lead agency).  
**Step 1 - Filter:** Identify Reclamation as author; stay on campsite-degradation material.

**Step 2 - Fetch:** https://www.usbr.gov/uc/envdocs/eis/gc/gcdOpsFEIS.html - Reclamation's chapter-by-chapter host for the March 1995 *Operation of Glen Canyon Dam* Final EIS. Links Cover/Summary and Chapter 3.  
**Step 2 - Verify:** Lead-agency copy (prompt never said "Bureau of Reclamation" or "recreation chapter").  
**Step 2 - Filter:** Pull PDFs from this index.

**Step 3 - Fetch:** https://www.usbr.gov/uc/envdocs/eis/gc/pdfs/Cov-con/cov-con.pdf - Cover/Summary. Preferred alternative is the **Modified Low Fluctuating Flow Alternative**.  
**Step 3 - Verify:** Matches the prompt's MLFF constraint.  
**Step 3 - Filter:** Correct FEIS / correct preferred alternative before Chapter 3.

**Step 4 - Fetch (twin):** https://www.usbr.gov/uc/envdocs/eis/gc/pdfs/Ch3/chap3-1.pdf - Chapter 3, printed page **156**. Selectable prose: in narrow (critical) reaches, erosion was the primary cause of campsite degradation; encroachment accounted for nearly **50** percent of the campsite degradation in wider (noncritical) reaches (**figure III-36**).  
**Step 4 - Verify:** Narrative twin is "nearly 50 percent" for noncritical vegetation; no Critical Overgrown percent in text. Figure callout is what the prompt requires the solver to identify.  
**Step 4 - Filter:** Reject **50%** and stay off the Non-Critical pie.

**Step 5 - Fetch (answer):** same Chapter 3 PDF, printed page **156** - **Figure III-36**, "Number of camps degraded by reach type and type of degradation." Two raster pies. Critical Reaches: Eroded **71% (29)**; **Overgrown 15% (6)**; Other **7% (3)**; Eroded/Overgrown **7% (3)**. Non-Critical Overgrown is **4% (8)**. Pie numerals are image-only (no Critical Overgrown `15%` recreation pie label in the Chapter 3 text layer; unrelated "15 percent" hits elsewhere are not this slice).  
**Step 5 - Verify:** Critical **Overgrown** slice is **15%**.  
**Step 5 - Filter:** Lock **15%**. Dump **50%**, Critical **71% / 7% / 7%**, and Non-Critical Overgrown **4%**.

**Step 6 - Fetch (mirror check):** http://www.riversimulator.org/Resources/USBR/LTEP/1995EIS.pdf - full-bound FEIS. Text search finds the "nearly 50 percent" line and does not surface Figure III-36's Critical **Overgrown 15%** as a recreation pie label (pie is raster).  
**Step 6 - Verify:** Answer is chart-image-only; twin is what search surfaces next to the figure callout.  
**Step 6 - Filter:** Keep **15%**.

---

## Verification Sources

1. https://en.wikipedia.org/wiki/Glen_Canyon_Dam - exact clues: body text "EIS completed March 21, 1995"; References entry *Operation of Glen Canyon Dam... final environmental impact statement* (1995, U.S. Bureau of Reclamation); External links "1995 Glen Canyon EIS" to the usbr.gov chapter index.  
2. https://www.usbr.gov/uc/envdocs/eis/gc/gcdOpsFEIS.html - official FEIS chapter index.  
3. https://www.usbr.gov/uc/envdocs/eis/gc/pdfs/Cov-con/cov-con.pdf - Modified Low Fluctuating Flow preferred alternative.  
4. https://www.usbr.gov/uc/envdocs/eis/gc/pdfs/Ch3/chap3-1.pdf - printed p.156 twin "nearly 50 percent"; Figure III-36 Critical **Overgrown = 15%**.  
5. http://www.riversimulator.org/Resources/USBR/LTEP/1995EIS.pdf - full mirror; prose twin searchable; pie slice image-only.

---

## Failure justification

The model answered **17%**, after browsing and naming Figure III-36 / Critical Reaches. The Critical **Overgrown** slice is **15% (6)**, not 17%. It also leaned on a secondary campsite paper and inverted Non-Critical categories. So it never recovered the true Critical Overgrown label from the raster pie.

---

## Checklist

- [x] One atomic answer (`15%`)  
- [x] Prompt word count 70-150 (83)  
- [x] Timeless (1995 FEIS)  
- [x] No website names in prompt  
- [x] Official usbr.gov host  
- [x] No self-authored verification pages  
- [x] Answer only on raster chart; twins in searchable text  
- [x] Observed fail = chart near-miss (`17%` ≠ `15%`)  
- [x] GT ↔ Verification Sources URL parity  
- [x] No em dashes  
- [x] Lean discovery: no agency / chapter / figure-number spoon-feeding  
- [x] Distinct from Non-Critical Overgrown `4%` stump on the same figure  
