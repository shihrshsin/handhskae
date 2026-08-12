# Legal - Glen Canyon Dam 1995 FEIS Fig. III-37 inundation 5,000 to 8,000 cfs

**Answer:** `5%`  
**Famous twin:** `35%` - same-page body text ("An average of 35 percent of potential campsite area is inundated when releases increase from 5,000 to 25,000 cfs").  
**Secondary traps:** `18%` (5,000 to 15,000 bar); `25%` (15,000 to 25,000 bar); `36%` (size-class change prose on the same page).  
**Observed model failure:** Answered `9%` (misread/hallucinated the 5,000 to 8,000 inundation bar on Figure III-37 after browsing usbr.gov Chapter 3).  
**Doc:** Same 1995 Glen Canyon Dam operations FEIS Chapter 3 / Figure III-37 as the `18%` and `25%` inundation stumps - different bar (5-8 instead of 5-15 / 15-25).

---

## Prompt (94 words)

In the Bureau of Reclamation's 1995 final environmental impact statement on the operation of Glen Canyon Dam, whose preferred alternative was the Modified Low Fluctuating Flow Alternative, the recreation analysis includes a bar chart of the percentage of camping-beach area inundated between selected discharge ranges. Body text notes that an average of 35 percent of potential campsite area is inundated when releases increase from 5,000 to 25,000 cubic feet per second. For the increase from 5,000 to 8,000 cubic feet per second, what exact percentage of beach area does that chart show as inundated?

---

## Answer

`5%`

---

## Golden Trajectory

**Step 1 - Search:** `"Operation of Glen Canyon Dam" "Final Environmental Impact Statement" 1995 "Modified Low Fluctuating Flow"`  
**Step 1 - Fetch:** https://en.wikipedia.org/wiki/Glen_Canyon_Dam - Environmental issues section cites the 1995 federal operations EIS. Document ID only; no preferred-alternative name and no inundation-bar percentages.  
**Step 1 - Verify:** Right FEIS family.  
**Step 1 - Filter:** Stay on that FEIS's recreation / camping-beach inundation material.

**Step 2 - Fetch:** https://www.usbr.gov/uc/envdocs/eis/gc/gcdOpsFEIS.html - Reclamation's chapter-by-chapter host for the March 1995 *Operation of Glen Canyon Dam* Final EIS. Links Cover/Summary and Chapter 3.  
**Step 2 - Verify:** Lead-agency copy.  
**Step 2 - Filter:** Pull PDFs from this index.

**Step 3 - Fetch:** https://www.usbr.gov/uc/envdocs/eis/gc/pdfs/Cov-con/cov-con.pdf - Cover/Summary. Preferred alternative is the **Modified Low Fluctuating Flow Alternative**.  
**Step 3 - Verify:** Matches the prompt's MLFF constraint.  
**Step 3 - Filter:** Correct FEIS / correct preferred alternative before Chapter 3.

**Step 4 - Fetch (twin):** https://www.usbr.gov/uc/envdocs/eis/gc/pdfs/Ch3/chap3-1.pdf - Chapter 3, printed page **157**. Selectable prose: "An average of **35** percent of potential campsite area is inundated when releases increase from 5,000 to 25,000 cfs." Also nearby: about **36** percent of small and medium sites change size class when releases drop to 15,000 cfs or less.  
**Step 4 - Verify:** **35%** is the prompt's twin (5,000 to 25,000 range); **36%** is a size-class sentence, not an inundation bar.  
**Step 4 - Filter:** Reject **35%** and **36%** as the 5,000 to 8,000 inundation-bar value.

**Step 5 - Fetch (answer):** same Chapter 3 PDF, printed page **157** (Chapter PDF page **92**) - **Figure III-37**, "Percentage of beach area inundated between discharges." Raster bar chart. Bar labels: 5,000 to 8,000 cfs = **5%**; 5,000 to 15,000 cfs = **18%**; 15,000 to 25,000 cfs = **25%**; 5,000 to 25,000 cfs = **35%**.  
**Step 5 - Verify:** The 5,000 to 8,000 cfs bar reads **5%**.  
**Step 5 - Filter:** Lock **5%**. Dump **35%**, **18%**, **25%**, and **36%**. Confirm the fourth bar (**35%**) matches the body-text twin, calibrating the chart scale.

**Step 6 - Fetch (mirror check):** http://www.riversimulator.org/Resources/USBR/LTEP/1995EIS.pdf - full-bound FEIS. Text search surfaces the body-text **35%** (5,000 to 25,000) and does not return the recreation inundation-bar **5%** for the 5-8 range, because Figure III-37 is a raster image with no text layer for that bar label. Unrelated "5 percent" hits elsewhere in the bound volume are not this bar.  
**Step 6 - Verify:** Answer is chart-image-only; twin is what search surfaces.  
**Step 6 - Filter:** Keep **5%**.

---

## Verification Sources

1. https://en.wikipedia.org/wiki/Glen_Canyon_Dam - 1995 operations FEIS exists.  
2. https://www.usbr.gov/uc/envdocs/eis/gc/gcdOpsFEIS.html - official FEIS chapter index.  
3. https://www.usbr.gov/uc/envdocs/eis/gc/pdfs/Cov-con/cov-con.pdf - Modified Low Fluctuating Flow preferred alternative.  
4. https://www.usbr.gov/uc/envdocs/eis/gc/pdfs/Ch3/chap3-1.pdf - printed p.157 twin **35%**; Figure III-37 5,000 to 8,000 cfs = **5%**.  
5. http://www.riversimulator.org/Resources/USBR/LTEP/1995EIS.pdf - full mirror; prose twin searchable; bar **5%** image-only.

---

## Failure justification

*(Fill after live ChatGPT web-browsing run.)*

---

## Checklist

- [x] One atomic answer (`5%`)  
- [x] Timeless (1995 FEIS)  
- [x] No website names in prompt  
- [x] Official usbr.gov host  
- [x] No self-authored verification pages  
- [x] Answer only on raster chart; twins in searchable text  
- [ ] Observed fail recorded  
- [x] GT ↔ Verification Sources URL parity  
- [x] No em dashes  
- [x] Distinct from `18%` / `25%` bars on the same figure  
