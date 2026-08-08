# Shopping - NBS Circ. 70 white-lead first-coat benzol (2/3 pint)

**Answer:** `2/3`  
**Famous twin:** `1/2` - PDF text layer OCR of that benzol cell is garbled as `Vz` (reads like a half); `1/2` also appears elsewhere in the circular’s measure tables.  
**Same-table traps:** raw linseed oil **3/4** pint; turpentine **1 3/4** pints; Japan drier **1** ounce (yellow pine/cypress first coat).  
**Why hard / deeper than Differin & Nizoral:** 1917 grainy additions table cell, not a modern FDA EA numeral. Whole-PDF text search has **no** `2/3`. Adjacent prose only says “a small amount of benzol.” Tesseract often invents other fractions. Not quoted on the open web with this recipe.

---

## Prompt (85 words)

A householder is mixing white-lead paint on the job for outside work, following an early Bureau of Standards household materials circular. The base batch is 15.5 pounds of white-lead paste, 3 pints of raw linseed oil, and 5 ounces of turpentine Japan drier. For the first coat on yellow pine or cypress, the additions table calls for extra raw linseed oil, turpentine, Japan drier, and benzol. How many pints of benzol does that first-coat yellow pine or cypress column specify to add to the base?

---

## Answer

`2/3`

---

## Golden Trajectory

**Step 1 - Search:** `"Materials for the Household" "Bureau of Standards" Circular 70 white-lead paint benzol`

**Step 2 - Fetch:** https://doi.org/10.6028/nbs.circ.70 - Circular of the Bureau of Standards no. 70: *Materials for the Household* (1917).

**Step 3 - Fetch:** https://api.crossref.org/works/10.6028/nbs.circ.70 - Crossref metadata confirming title / NBS CIRC 70 identity.

**Step 4 - Verify:** Right federal household materials circular for on-the-job paint mixing guidance.

**Step 5 - Filter:** Need the “White Lead Mixed on the Job, for Outside Exposure” additions table, first coat, yellow pine or cypress column, benzol row, not the ready-mixed percent recipes below and not the basswood column blanks.

**Step 6 - Fetch (twin / trap):** https://nvlpubs.nist.gov/nistpubs/Legacy/circ/nbscircular70.pdf - PDF page **123** / printed **121**. Text layer shows the benzol unit line and a garbled cell `Vz` (½-like). Prose above only says add “a small amount of benzol.” Reject `1/2`.

**Step 7 - Fetch (answer):** same PDF page **123** / printed **121** - additions table, Benzol / pint row, Yellow pine or cypress first-coat cell = **2/3**.

**Step 8 - Verify:** Whole-PDF text search finds no `2/3`. Answer = **2/3**.

**Step 9 - Twin:** OCR/text suggests **1/2** (`Vz`); true printed fraction is **2/3**.

---

## Verification Sources

1. https://doi.org/10.6028/nbs.circ.70 - NBS Circular 70 metadata.  
2. https://api.crossref.org/works/10.6028/nbs.circ.70 - Crossref work record for Circ. 70.  
3. https://nvlpubs.nist.gov/nistpubs/Legacy/circ/nbscircular70.pdf - PDF page 123 / printed 121, benzol first-coat yellow pine/cypress cell **2/3**; text-layer twin `Vz` / **1/2**.

---

## Failure justification (expected)

Differin and Nizoral failed because modern FDA scans had clear, discoverable numerals. Here the model that reaches Circ. 70 still tends to trust the text-layer `Vz` as **1/2**, or grab neighboring **3/4** / **1 3/4**, or follow web priming advice (“about a pint” / “40 percent benzol”) instead of the tiny printed **2/3** cell.

---

## Checklist

- [x] One atomic answer (`2/3`)  
- [x] Timeless (1917 NBS Circ. 70)  
- [x] No website names in prompt  
- [x] 3+ hops  
- [x] No arithmetic  
- [x] In-page locations on every Fetch  
- [x] No archive.org verification links  
- [x] GT <-> Verification Sources URL parity  
- [x] Answer absent from text layer; twin present as OCR garble  
- [x] No em dashes  
- [x] Shopping-relevant (household paint materials / on-the-job mixing)  
- [x] Not a clean modern FDA EA table  
- [x] Not a Staples-style labeled bar chart  
