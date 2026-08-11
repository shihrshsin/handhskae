# Legal — Glen Canyon Dam 1995 FEIS camping-beach table total

**Answer:** `239`  
**Famous twins:** `226` (suitable beaches after decline); `333` (1975 inventory). Secondary: `37` (low-water-only add-ons in parentheses); modern reuse `276` (=239+37).  
**Pattern:** Official usbr.gov Chapter 3 raster table (image-only page); twins live in selectable body text on the prior page.

---

## Prompt (112 words)

In the Bureau of Reclamation’s 1995 final environmental impact statement on the operation of Glen Canyon Dam—whose preferred alternative was the Modified Low Fluctuating Flow Alternative—the recreation analysis cites a 1975 inventory of about 333 campsites in the river corridor and later states that suitable camping beaches above the new high-water zone had declined to 226 sites. On the reach-by-reach distribution table of camping beaches by size class (small, medium, and large), excluding the parenthetical counts of additional beaches available only at low water, what grand total number of camping beaches does that table report?

---

## Answer

`239`

---

## Golden Trajectory

**Step 1 — Search:** `"Operation of Glen Canyon Dam" "Final Environmental Impact Statement" 1995 "Modified Low Fluctuating Flow"`  
**Step 1 — Fetch:** https://en.wikipedia.org/wiki/Glen_Canyon_Dam — Environmental issues / operations discussion citing the 1995 federal operations EIS. Confirms the document exists; does not state the preferred-alternative name or the table total.  
**Step 1 — Verify:** Identifies Reclamation’s 1995 Glen Canyon Dam operations FEIS as the right document family.  
**Step 1 — Filter:** Narrows to that FEIS’s recreation / camping-beach analysis—not unrelated Glen Canyon visitor pages.

**Step 2 — Fetch:** https://www.usbr.gov/uc/envdocs/eis/gc/gcdOpsFEIS.html — Bureau of Reclamation’s official chapter-by-chapter host for the *Operation of Glen Canyon Dam Final Environmental Impact Statement* (March 1995). Index lists Cover/Summary and Chapter 3.  
**Step 2 — Verify:** Lead-agency host for the FEIS chapters.  
**Step 2 — Filter:** Use usbr.gov chapter PDFs as primary, not secondary summaries.

**Step 3 — Fetch:** https://www.usbr.gov/uc/envdocs/eis/gc/pdfs/Cov-con/cov-con.pdf — Cover/Summary. Preferred alternative is the **Modified Low Fluctuating Flow Alternative**.  
**Step 3 — Verify:** Matches the prompt’s preferred-alternative constraint.  
**Step 3 — Filter:** Locks MLFF as the FEIS preferred alternative before opening Chapter 3.

**Step 4 — Fetch (twins):** https://www.usbr.gov/uc/envdocs/eis/gc/pdfs/Ch3/chap3-1.pdf — Chapter 3, printed page **156** (selectable text): *“An inventory of these camping beaches in 1975 listed about **333** campsites within the river corridor…”*; *“the total number of suitable camping beaches above the new high water zone had declined to **226** sites, a 48-percent decline…”*  
**Step 4 — Verify:** Surfaces the prompt’s **333** and **226** figures in body text.  
**Step 4 — Filter:** Reject **333** and **226** as the table grand total; those are inventory/decline prose figures, not Table III-13’s total.

**Step 5 — Fetch (answer):** same Chapter 3 PDF, printed page **158** / Chapter PDF page **93** — **Table III-13**, “Distribution of camping beaches by reach” (Kearsley and Warren, 1992). The page is a **raster scan with no usable text layer**. Size-class columns Small / Medium / Large; Totals row reads **47 / 102 / 90**, grand total **239 (37)**. Note under the table: numbers in parentheses are additional beaches available at low water (15,000 cfs or less) only.  
**Step 5 — Verify:** Excluding the parenthetical low-water **37**, the table’s grand total is **239**.  
**Step 5 — Filter:** Final lock on **239**; drops **226**, **333**, **37**, and **276** (239+37).

**Step 6 — Fetch (twin mirror):** http://www.riversimulator.org/Resources/USBR/LTEP/1995EIS.pdf — full-bound FEIS. Full-text search returns body-text **226** and **333** and does **not** return **239**, because Table III-13 sits on a zero-text raster page (printed p.158 / full-PDF ~p.180).  
**Step 6 — Verify:** Confirms **239** is chart/table-image-only; searchable twins are the prose figures.  
**Step 6 — Filter:** Keeps **239**.

---

## Verification Sources

1. https://en.wikipedia.org/wiki/Glen_Canyon_Dam — 1995 operations FEIS exists.  
2. https://www.usbr.gov/uc/envdocs/eis/gc/gcdOpsFEIS.html — official FEIS chapter index.  
3. https://www.usbr.gov/uc/envdocs/eis/gc/pdfs/Cov-con/cov-con.pdf — Modified Low Fluctuating Flow preferred alternative.  
4. https://www.usbr.gov/uc/envdocs/eis/gc/pdfs/Ch3/chap3-1.pdf — printed p.156 twins **333** / **226**; printed p.158 Table III-13 grand total **239** (exclude parenthetical **37**).  
5. http://www.riversimulator.org/Resources/USBR/LTEP/1995EIS.pdf — full-bound mirror; text search hits **226**/**333**, not **239**.

---

## Failure justification

Models answer **226** or **333** from selectable Chapter 3 prose (or **276** by adding the low-water **37**) and never read the zero-text Table III-13 page for the base grand total **239**.

---

## Checklist

- [x] One atomic answer (`239`)  
- [x] Timeless (1995 FEIS)  
- [x] No website names in prompt  
- [x] Official usbr.gov lead-agency host (Glen Canyon QC pattern)  
- [x] No self-authored verification pages  
- [x] Answer only on raster table; twins in searchable text  
- [x] GT ↔ Verification Sources URL parity  
- [x] Unambiguous: exclude parenthetical low-water counts  
- [x] Different figure from beach-inundation `18%` bar chart  
