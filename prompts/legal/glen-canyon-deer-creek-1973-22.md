# Legal - Glen Canyon Dam 1995 FEIS Fig. III-38 Deer Creek 1973

**Answer:** `2.2`  
**Searchable distractors:** `2.3` (Deer Creek in body text - 1991 chart bar); `1.0` (corridor-wide average).  
**Secondary traps:** `3.6` (Deer Creek 1983); `1.1` / `0.7` (1991 Non-critical / Critical).  
**Doc:** Same FEIS Chapter 3 / Figure III-38 as the Deer Creek 1983 `3.6` stump - different year bar (1973).

---

## Prompt (92 words)

In the 1995 final environmental impact statement on the operation of Glen Canyon Dam whose preferred alternative was the Modified Low Fluctuating Flow Alternative, the text reports that campsites average 1.0 per mile overall and that Deer Creek has more sites per mile than any other reach at 2.3. Setting aside those 1991-era narrative figures, turn to the campsites-per-mile comparison figure those sentences cite for the river corridor. What exact average campsites-per-mile value does that figure show for the Deer Creek reach in 1973? Report the printed chart value only.

---

## Answer

`2.2`

---

## Golden Trajectory

**Step 1 - Search:** `"Operation of Glen Canyon Dam" "Final Environmental Impact Statement" 1995 "Modified Low Fluctuating Flow"`  
**Step 1 - Fetch:** https://en.wikipedia.org/wiki/Glen_Canyon_Dam - Exact on-page clues: (a) body text *"The EIS completed March 21, 1995 cemented some restrictions on dam operations..."*; (b) References: *U.S. Bureau of Reclamation (1995). Operation of Glen Canyon Dam: Colorado River Storage Project, Arizona: final environmental impact statement*; (c) External links **"1995 Glen Canyon EIS"** → https://www.usbr.gov/uc/envdocs/eis/gc/gcdOpsFEIS.html.  
**Step 1 - Verify:** Page names the 1995 *Operation of Glen Canyon Dam* Final EIS and Reclamation host.  
**Step 1 - Filter:** Identify Reclamation as author; stay on camping-beach / campsites-per-mile material.

**Step 2 - Search:** From that Wikipedia page, open External links **"1995 Glen Canyon EIS"**.  
**Step 2 - Fetch:** https://www.usbr.gov/uc/envdocs/eis/gc/gcdOpsFEIS.html - Official FEIS chapter index.  
**Step 2 - Verify:** Lead-agency copy.  
**Step 2 - Filter:** Use only PDFs linked from this index.

**Step 3 - Search:** On the FEIS index, open **"Cover Sheet, Table Of Contents, Etc."** (`cov-con.pdf`).  
**Step 3 - Fetch:** https://www.usbr.gov/uc/envdocs/eis/gc/pdfs/Cov-con/cov-con.pdf - Preferred alternative is the **Modified Low Fluctuating Flow Alternative**.  
**Step 3 - Verify:** Matches MLFF constraint.  
**Step 3 - Filter:** Confirm correct FEIS before Chapter 3.

**Step 4 - Search:** Return to FEIS index, open **"Chapter 3"** PDF; text-search `1.0 per mile` / `Deer Creek` / `2.3` / `figure III-38`.  
**Step 4 - Fetch:** https://www.usbr.gov/uc/envdocs/eis/gc/pdfs/Ch3/chap3-1.pdf - printed p.**157**. Selectable prose: campsites average **1.0** per mile; Deer Creek **2.3** sites per mile; callout to **figure III-38**.  
**Step 4 - Verify:** Those are 1991-era narrative figures; prose does not state the 1973 Deer Creek bar.  
**Step 4 - Filter:** Reject **1.0** and **2.3** as the 1973 Deer Creek chart value. Proceed to the cited figure.

**Step 5 - Search:** Same Chapter 3 PDF, turn to printed p.**158** (zero-text scan) and view **Figure III-38**.  
**Step 5 - Fetch:** https://www.usbr.gov/uc/envdocs/eis/gc/pdfs/Ch3/chap3-1.pdf - printed p.**158**. Figure III-38, "Number of campsites per mile by type of reach, 1973, 1983, and 1991." Deer Creek (stippled) bars print: **1973 = 2.2**; **1983 = 3.6**; **1991 = 2.3**. Labels are on the official scanned figure.  
**Step 5 - Verify:** 1973 Deer Creek label is **2.2**.  
**Step 5 - Filter:** Record **2.2**. Discard **2.3**, **1.0**, and **3.6**.

**Step 6 - Search:** `"Operation of Glen Canyon Dam" 1995 EIS filetype:pdf` / riversimulator full mirror; text-search `2.3` / `1.0 per mile`.  
**Step 6 - Fetch:** http://www.riversimulator.org/Resources/USBR/LTEP/1995EIS.pdf - finds the **1.0** / **2.3** prose; does not return Deer Creek **1973 = 2.2** as selectable chart text.  
**Step 6 - Verify:** Confirms the 1973 value comes from official figure labels, not searchable prose.  
**Step 6 - Filter:** Retain **2.2**.

---

## Verification Sources

1. https://en.wikipedia.org/wiki/Glen_Canyon_Dam - exact March 21, 1995 EIS prose; 1995 FEIS reference; External links "1995 Glen Canyon EIS"  
2. https://www.usbr.gov/uc/envdocs/eis/gc/gcdOpsFEIS.html - official FEIS chapter index  
3. https://www.usbr.gov/uc/envdocs/eis/gc/pdfs/Cov-con/cov-con.pdf - Modified Low Fluctuating Flow preferred alternative  
4. https://www.usbr.gov/uc/envdocs/eis/gc/pdfs/Ch3/chap3-1.pdf - p.157 distractors **1.0** / **2.3**; p.158 Fig. III-38 Deer Creek **1973 = 2.2**  
5. http://www.riversimulator.org/Resources/USBR/LTEP/1995EIS.pdf - full mirror  

---

## Failure justification

The model reached the correct lead-agency Chapter 3 PDF and named Figure III-38, but reported **1.5** campsites per mile for Deer Creek in 1973. On the official scanned figure the Deer Creek (stippled) **1973** bar is labeled **2.2**; **2.3** is the 1991 Deer Creek bar (also stated in the adjacent prose), and **3.6** is 1983. The answer **1.5** does not match any printed Deer Creek year label on Figure III-38. The model treated a misread or invented chart value as the 1973 Deer Creek figure while citing the right PDF, so it failed the figure-label read.
