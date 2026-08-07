# Legal — Glen Canyon Dam 1995 EIS beach inundation (5,000→15,000 cfs)

**Answer:** `18%`  
**Famous twin:** `35%` — body text on the same page (“An average of 35 percent of potential campsite area is inundated when releases increase from 5,000 to 25,000 cfs”).

---

## Prompt (98 words)

In the Bureau of Reclamation’s 1995 final environmental impact statement on the operation of Glen Canyon Dam—whose preferred alternative was the Modified Low Fluctuating Flow Alternative—the recreation analysis includes a bar chart of the percentage of camping-beach area inundated between selected discharge ranges. For the increase from 5,000 to 15,000 cubic feet per second, what exact percentage of beach area does that chart show as inundated?

---

## Answer

`18%`

---

## Golden Trajectory

**Step 1 — Search:** `1995 environmental impact statement "Glen Canyon Dam" operations "modified low fluctuating flow" Bureau of Reclamation`

**Step 2 — Fetch:** https://en.wikipedia.org/wiki/Glen_Canyon_Dam — **Environmental issues** / operations discussion and references citing the 1995 federal EIS on operation of Glen Canyon Dam (Colorado River Storage Project). Confirms the document exists; does **not** state the preferred-alternative name.

**Step 3 — Fetch:** http://www.riversimulator.org/Resources/USBR/LTEP/1995EIS.pdf — **PDF page 4** (EIS summary / cover-summary sheet): preferred alternative is the **Modified Low Fluctuating Flow Alternative**.

**Step 4 — Verify:** Document is the 1995 *Operation of Glen Canyon Dam* Final EIS; preferred alternative matches the prompt.

**Step 5 — Filter:** Fixes which EIS and that the question is about its recreation (camping-beach inundation) analysis.

**Step 6 — Fetch:** same EIS PDF — recreation section, **printed page 157 (PDF page 179)**. **Figure III-37**, “Percentage of beach area inundated between discharges,” is a **raster** bar chart (scanned image, no text layer on the figure itself). Bar labels read: 5,000→8,000 cfs = **5%**; 5,000→15,000 cfs = **18%**; 15,000→25,000 cfs = **25%**; 5,000→25,000 cfs = **35%**.

**Step 7 — Verify:** The 5,000→15,000 cfs bar reads **18%**.

**Step 8 — Calibrate (internal check):** Adjacent body text on the same page states only: *“An average of 35 percent of potential campsite area is inundated when releases increase from 5,000 to 25,000 cfs.”* That **35%** matches the chart’s **fourth bar** (5,000→25,000), confirming the bar scale/labels are read correctly—so the second bar’s **18%** is trustworthy.

**Step 9 — Confirm the twin:** Full-text search of the PDF surfaces the body-text **35%** (5,000→25,000) and does **not** return **18%**, because Figure III-37 is a raster image with no text layer; the 5,000→15,000 value is only recoverable by reading the chart image.

---

## Verification Sources

1. http://www.riversimulator.org/Resources/USBR/LTEP/1995EIS.pdf — PDF page 4 (Modified Low Fluctuating Flow Alternative); PDF page 179 / printed page 157, Figure III-37 (18%) and adjacent 35% body text.  
2. https://en.wikipedia.org/wiki/Glen_Canyon_Dam — Environmental issues / operations; identifies the 1995 operations EIS.

---

## Checklist fixes applied

| Ask | Resolution |
|---|---|
| Don’t credit Wikipedia for “Modified Low Fluctuating Flow Alternative” | MLFF confirmed on **EIS PDF page 4**, not wiki |
| Sharper point on why 18% is hard | Figure III-37 is a **raster image with no text layer**; PDF text search returns nothing for 18% |
| Use internal calibration | Body-text **35%** (5k→25k) matches the **fourth bar**, calibrating the chart before accepting **18%** |
