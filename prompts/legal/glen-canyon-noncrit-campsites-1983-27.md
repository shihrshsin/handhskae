# Legal - Glen Canyon Dam 1995 FEIS Fig. III-38 Non-critical 1983

**Answer:** `2.7`  
**Famous twins:** `1.1` (noncritical reaches average in body text - the 1991 chart bar); `2.3` (Deer Creek in body text); `1.0` (corridor-wide average).  
**Secondary traps:** `1.9` (1983 Total / 1973 Non-critical); `0.9` (1983 Critical); `3.6` (1983 Deer Creek, prior stump).  
**Observed model failure:** Answered `1.7` (misread the 1983 Non-critical bar on Figure III-38 after citing usbr.gov Chapter 3; correctly used the **1.1** 1991 prose twin as contrast). Earlier browsing run answered `2.3` (Deer Creek twin).  
**Doc:** Same 1995 Glen Canyon Dam operations FEIS Chapter 3 / Figure III-38 as the Deer Creek `3.6` stump - different bar (Non-critical 1983).

---

## Prompt (79 words)

In the Bureau of Reclamation's 1995 final environmental impact statement on the operation of Glen Canyon Dam, whose preferred alternative was the Modified Low Fluctuating Flow Alternative, the recreation chapter states that campsites in noncritical reaches average 1.1 per mile and that Deer Creek has 2.3 sites per mile. On the accompanying bar chart of average campsites per mile by reach type for 1973, 1983, and 1991, what exact average campsites-per-mile value is shown for non-critical reaches in 1983?

---

## Answer

`2.7`

---

## Golden Trajectory

**Step 1 - Search:** `"Operation of Glen Canyon Dam" "Final Environmental Impact Statement" 1995 "Modified Low Fluctuating Flow"`  
**Step 1 - Fetch:** https://en.wikipedia.org/wiki/Glen_Canyon_Dam - Environmental issues section cites the 1995 federal operations EIS. Document ID only; no preferred-alternative name and no campsites-per-mile chart values.  
**Step 1 - Verify:** Right FEIS family.  
**Step 1 - Filter:** Stay on that FEIS's recreation / camping-beach material.

**Step 2 - Fetch:** https://www.usbr.gov/uc/envdocs/eis/gc/gcdOpsFEIS.html - Reclamation's chapter-by-chapter host for the March 1995 *Operation of Glen Canyon Dam* Final EIS. Links Cover/Summary and Chapter 3.  
**Step 2 - Verify:** Lead-agency copy.  
**Step 2 - Filter:** Pull PDFs from this index.

**Step 3 - Fetch:** https://www.usbr.gov/uc/envdocs/eis/gc/pdfs/Cov-con/cov-con.pdf - Cover/Summary. Preferred alternative is the **Modified Low Fluctuating Flow Alternative**.  
**Step 3 - Verify:** Matches the prompt's MLFF constraint.  
**Step 3 - Filter:** Correct FEIS / correct preferred alternative before Chapter 3.

**Step 4 - Fetch (twins):** https://www.usbr.gov/uc/envdocs/eis/gc/pdfs/Ch3/chap3-1.pdf - Chapter 3, printed page **157**. Selectable prose: campsites average **1.0** per mile; critical **0.7** / noncritical **1.1**; Deer Creek **2.3** sites per mile; callout to figure III-38.  
**Step 4 - Verify:** Those are the prompt's twin figures - 1991-era narrative values, not the 1983 Non-critical bar.  
**Step 4 - Filter:** Reject **1.1**, **2.3**, and **1.0** as the 1983 Non-critical chart value.

**Step 5 - Fetch (answer):** same Chapter 3 PDF, printed page **158** (Chapter PDF page **93**) - **Figure III-38**, "Number of campsites per mile by type of reach, 1973, 1983, and 1991" (modified from Kearsley and Warren, 1993). Full page is a zero-text raster scan. 1983 bars: Critical **0.9**; Non-critical **2.7**; Deer Creek **3.6**; Total **1.9**. Footnote: *1983 does not include "small" camps.  
**Step 5 - Verify:** 1983 Non-critical bar label is **2.7**.  
**Step 5 - Filter:** Lock **2.7**. Dump **1.1**, **2.3**, **1.0**, **3.6**, and other 1983 bars (**0.9** / **1.9**).

**Step 6 - Fetch (mirror check):** http://www.riversimulator.org/Resources/USBR/LTEP/1995EIS.pdf - full-bound FEIS. Text search finds the **1.1** / **2.3** / **1.0** prose on printed p.157 and does not surface Figure III-38's Non-critical **2.7** as a selectable recreation chart label (figure sits on the zero-text p.158 scan; unrelated "2.7" hits elsewhere are not this bar).  
**Step 6 - Verify:** Answer is chart-image-only; twins are what search surfaces.  
**Step 6 - Filter:** Keep **2.7**.

---

## Verification Sources

1. https://en.wikipedia.org/wiki/Glen_Canyon_Dam - 1995 operations FEIS exists.  
2. https://www.usbr.gov/uc/envdocs/eis/gc/gcdOpsFEIS.html - official FEIS chapter index.  
3. https://www.usbr.gov/uc/envdocs/eis/gc/pdfs/Cov-con/cov-con.pdf - Modified Low Fluctuating Flow preferred alternative.  
4. https://www.usbr.gov/uc/envdocs/eis/gc/pdfs/Ch3/chap3-1.pdf - printed p.157 twins **1.1** / **2.3**; printed p.158 Figure III-38 Non-critical **1983 = 2.7**.  
5. http://www.riversimulator.org/Resources/USBR/LTEP/1995EIS.pdf - full mirror; prose twins searchable; 1983 Non-critical bar image-only.

---

## Failure justification

The model answered **1.7**, citing the usbr.gov Chapter 3 PDF and contrasting that against the **1.1** 1991 noncritical prose figure. Figure III-38's 1983 Non-critical bar is **2.7**, not 1.7. That numeral is image-only on the zero-text chart page, so the model never recovered the true bar label from the raster. An earlier browsing run made a different error with the Deer Creek twin **2.3**.

---

## Checklist

- [x] One atomic answer (`2.7`)  
- [x] Timeless (1995 FEIS)  
- [x] No website names in prompt  
- [x] Official usbr.gov host  
- [x] No self-authored verification pages  
- [x] Answer only on raster chart; twins in searchable text  
- [x] Observed fail = chart misread (`1.7` / earlier twin `2.3` ≠ `2.7`)  
- [x] GT ↔ Verification Sources URL parity  
- [x] No em dashes  
- [x] Distinct from Deer Creek `3.6` stump on the same figure  
