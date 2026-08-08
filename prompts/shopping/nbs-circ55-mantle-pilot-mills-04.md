# Shopping - NBS Circ. 55 Mantle Pilot mean gas cost (0.4 mills)

**Answer:** `0.4 mills`  
**Famous twin (same page, text layer):** heater pilot-flame cost stated as **one-tenth of a cent per hour** (= 1 mill), which is a different appliance class than the Mantle Pilot lighting bar.  
**Searchable label twin:** text layer contains `Mantle Pilot` (and other appliance labels) but none of the Mantle Pilot bar numerals (`.3` / `.5` / `.4`).  
**Same-page traps:** Fish Tail Burner mean **6**; Junior Upright Mantle mean **1.5**; water heater **3 to 8 cents**; room heaters **5 to 12 cents**; match **one-tenth mill**.  
**Why hard:** Answer is only on a grainy 1915 image bar chart (Fig. 41, smallest row). Whole-PDF text search does not return `.4` / `0.4` for this chart. Web search for mantle pilot / gas cost returns modern BTU blogs, not this numeral. Harder than Differin: not a headline Rx-to-OTC dossier; answer not in clear FDA prose.

---

## Prompt (95 words)

I'm trying to figure out what a household should expect to spend per hour to keep a mantle pilot lit on old municipal gas, using the early federal consumer measurement guidance that compared common gas lighting fixtures side by side. The chart prices gas at one dollar per thousand cubic feet and reports cost in mills (tenths of a cent), with a minimum, a maximum, and a mean marked on each bar. For the Mantle Pilot row specifically, what mean cost per hour does that chart give?

Please answer with just the mean in mills.

---

## Answer

`0.4 mills`

(Accept `.4 mills`, `0.4`, or `.4`.)

---

## Golden Trajectory

**Step 1 - Search:** `Bureau of Standards measurements for the household gas appliances cost per hour mills`

**Step 2 - Fetch:** https://doi.org/10.6028/nbs.circ.55 - Circular of the Bureau of Standards No. 55, Measurements for the Household (1915 GPO print of 1913 circular).

**Step 3 - Verify:** Confirms the federal household measurement circular covering gas meters, appliances, and consumer cost checks.

**Step 4 - Filter:** Need the comparative lighting-appliance cost chart in mills, not the water-heater prose costs and not the gas-meter dial readings.

**Step 5 - Fetch (twin / trap):** https://nvlpubs.nist.gov/nistpubs/Legacy/circ/nbscircular55.pdf - PDF page **102** (printed page **98**), text under Fig. 41: *The pilot-flame gas for these heaters would amount to one-tenth of a cent per hour.* Searchable twin; reject (heater pilot, wrong unit framing vs Mantle Pilot mean).

**Step 6 - Fetch (answer):** same PDF - PDF page **102** / printed **98**, **Fig. 41**. Chart legend: *NUMERALS REFER TO COST PER HOUR IN MILLS (TENTHS OF A CENT).* Bottom row **Mantle Pilot** bar: min `.3`, max `.5`, mean **`.4`**. Page text layer has the label `Mantle Pilot` but not `.4`.

**Step 7 - Verify:** `pdftotext` on page 102 returns no `.4` / `0.4` / `.3` / `1.5` / `3.5`. Answer = **0.4 mills**.

**Step 8 - Twin:** Search/text hits **one-tenth of a cent** (heater pilot) or modern pilot BTU costs; Mantle Pilot mean is image-only on Fig. 41.

---

## Verification Sources

1. https://doi.org/10.6028/nbs.circ.55 - NBS Circular 55 metadata.  
2. https://nvlpubs.nist.gov/nistpubs/Legacy/circ/nbscircular55.pdf - PDF page 102 / printed 98, Fig. 41 Mantle Pilot mean **0.4 mills**; same-page twin **one-tenth of a cent** (heater pilot).

---

## Failure justification (expected)

Models that find Circular 55 latch onto the extractable heater-pilot prose (**one-tenth of a cent** / 1 mill) or onto modern web pilot-light cost calculators, and never recover the image-only Mantle Pilot mean on Fig. 41. Adjacent-row OCR can also yield Junior Upright Mantle **1.5** or Fish Tail **6**. Unlike Differin, googling the product family plus FDA/retail keywords does not surface a clean quote of the answer.

---

## Checklist

- [x] One atomic answer (`0.4 mills`)  
- [x] Timeless (1915 NBS Circ. 55)  
- [x] No website names in prompt  
- [x] 3+ hops  
- [x] No arithmetic  
- [x] In-page locations on every Fetch  
- [x] No archive.org verification links  
- [x] GT <-> Verification Sources URL parity  
- [x] Image-only answer + searchable twin  
- [x] No em dashes  
- [x] OCR-hostile grainy 1915 chart (not Staples-class clean modern bar chart)  
- [x] Shopping-relevant (household gas lighting operating cost)  
- [x] Official nvlpubs curl-downloadable (verified from this VM)  
