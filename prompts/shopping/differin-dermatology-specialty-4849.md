# Shopping - Differin Rx-to-OTC adapalene dermatology specialty share (48-49%)

**Answer:** `48-49%`  
**Famous twin:** `169` - same Other Reviews PDF, medical-review section (PDF page 116, text layer): outcomes known for **169** pregnancies (109 healthy infants, etc.).  
**Same-page traps:** Physician Assistants **15%-17%**; Pediatricians **10%-16%**; overall TRx **7%** increase; single-ingredient **-16%**; combination **+37%**.  
**Why hard:** Answer sits in a long **image-only** OSE utilization stretch (PDF page 134 / printed p.11 of that scan block; Reference ID 3902112). `48-49%` is absent from the whole-PDF text layer. Not a labeled bar chart (Staples failure mode).

---

## Prompt (89 words)

In the mid-2010s, the acne gel sold as Differin 0.1% left the prescription counter and moved onto ordinary U.S. drugstore shelves as the first over-the-counter topical retinoid. While FDA reviewers were weighing that switch, they also mapped how adapalene was already moving through outpatient retail pharmacies. In the scanned specialty breakdown for dispensed adapalene prescriptions from December 2010 through November 2015, covering both single-ingredient adapalene and the benzoyl peroxide combinations, what share came from dermatology as the top prescribing specialty? Answer with the short percent range exactly as written.

---

## Answer

`48-49%`

---

## Golden Trajectory

**Step 1 - Search:** `Differin 0.1% adapalene FDA over-the-counter switch 2016`

**Step 2 - Fetch:** https://en.wikipedia.org/wiki/Adapalene - brand Differin; notes 2016 U.S. FDA approval of adapalene gel 0.1% for OTC acne use (first former Rx retinoid on the drugstore shelf).

**Step 3 - Fetch:** https://www.accessdata.fda.gov/scripts/cder/daf/index.cfm?event=overview.process&ApplNo=020380 - Drugs@FDA overview for NDA **020380** (Differin / adapalene); points to the 2016 supplement review package.

**Step 4 - Verify:** Confirms the Differin 0.1% gel Rx-to-OTC switch dossier.

**Step 5 - Filter:** Need the OSE drug-utilization specialty mix for dispensed retail adapalene TRx (Dec 2010-Nov 2015), not pregnancy counts and not the redacted volume chart.

**Step 6 - Fetch (twin / trap):** https://www.accessdata.fda.gov/drugsatfda_docs/nda/2016/020380Orig1s010OtherR.pdf - PDF page **116** (text layer): applicant pregnancy database, outcomes known for **169** pregnancies (109 healthy infants, 23 miscarriages, etc.). Searchable twin; reject.

**Step 7 - Fetch (answer):** same PDF - OSE utilization scan, **PDF page 134** (printed page **11** of that image block; Reference ID **3902112**). Page text layer is blank. Section **3.1.2 Dispensed Prescriptions by Prescribing Specialty**: *Dermatology was the top prescribing specialty for both adapalene and adapalene/benzoyl peroxide products at **48-49%** of dispensed prescriptions followed by Physician Assistants at 15%-17%...*

**Step 8 - Verify:** Whole-PDF text search does not return `48-49%`. Answer = **48-49%**.

**Step 9 - Twin:** Search hits **169**; the dermatology share is only on the image-only specialty prose.

---

## Verification Sources

1. https://en.wikipedia.org/wiki/Adapalene - Differin; 2016 OTC switch.  
2. https://www.accessdata.fda.gov/scripts/cder/daf/index.cfm?event=overview.process&ApplNo=020380 - Drugs@FDA NDA 020380.  
3. https://www.accessdata.fda.gov/drugsatfda_docs/nda/2016/020380Orig1s010OtherR.pdf - PDF page 134 / printed 11 (**48-49%**); PDF page 116 twin (**169**).

---

## Failure justification (expected)

Models that grep the Other Reviews PDF latch onto the pregnancy twin (**169**) or same-page retail traps (**15%-17%**, **7%**, **37%**) and never recover the image-only specialty sentence. Unlike the Staples bar-chart miss, the answer is buried running prose on a blank text-layer scan page, not a clean labeled chart numeral.

---

## Checklist

- [x] One atomic answer (`48-49%`)  
- [x] Timeless (2016 Differin switch dossier)  
- [x] No website names in prompt  
- [x] 3+ hops  
- [x] No arithmetic  
- [x] In-page locations on every Fetch  
- [x] No archive.org verification links  
- [x] GT <-> Verification Sources URL parity  
- [x] Image-only answer + searchable twin  
- [x] No em dashes  
- [x] Not a clear bar chart (Staples anti-pattern)  
