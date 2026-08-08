# Stump method playbook (Project Seal)

How we stump ChatGPT 5.5 Pro (web-browsing) for domain research prompts. Distilled from Celebrities, Business, Legal, Science & Tech, and Shopping runs, including the successful Shopping stump: NBS Circ. 70 benzol **2/3** (model answered **1/2**).

---

## 1. Goal

Build a 70–150 word prompt with one atomic answer that the model fails ≥4/8 times. The answer must be findable by a careful human with the golden trajectory, but easy for a browsing model to miss.

---

## 2. Package every task must include

1. **Prompt** (humanized, no website names, no em dashes)
2. **Answer** (one atomic value)
3. **Famous twin** (nearby wrong value)
4. **Golden Trajectory** (Search → Fetch → Verify → Filter, with URLs + in-page locations)
5. **Verification Sources** (3+, same URLs as GT)
6. **Failure justification** (prefer observed wrong answer)
7. **Checklist**

---

## 3. The winning formula

| Ingredient | Why |
|---|---|
| **Un-webbed value** | Not already quoted on Scribd/blogs/Wikipedia |
| **Image-only answer** | `pdftotext` does not contain the answer string |
| **Famous twin in text/OCR** | Model grabs the searchable wrong number |
| **Obscure official doc** | Not a headline package everyone opens in one hop |
| **OCR-hostile scan** | Grainy 1910s–1950s typewriter > clean modern Word PDF |
| **Natural binding** | Prompt points to the exact row/year/species without naming the PDF |

One-line north star:

> Hide the answer in an official scan with no text layer; leave a famous twin in searchable OCR/text; make the document obscure enough that clean vision never gets a free turn.

---

## 4. Method used to find the Shopping win (Circ 70 benzol 2/3)

### Failed attempts (and why)

| Attempt | Answer | Why model solved it |
|---|---|---|
| Differin specialty share | `48-49%` | Famous Rx-to-OTC → FDA OtherR; clear modern prose |
| Nizoral Year-5 wastewater | `11951.7` | Still an FDA EA table; vision/OCR read the numeral cleanly |
| Mantle Pilot mills chart | `0.4` | Rejected pre-ship: labeled bar chart (Staples failure mode) |

### What we switched to

Old **NBS Circular 70** (*Materials for the Household*, 1917) on `nvlpubs.nist.gov` / GovInfo.

1. Downloaded Circ. 70  
2. Searched for shopping-relevant tables (paint mixed on the job)  
3. Found additions table on PDF p.123 / printed p.121  
4. Confirmed benzol / yellow pine or cypress cell reads **2/3** on the image  
5. Confirmed whole-PDF text has **no** `2/3`  
6. Confirmed text layer garbles that cell as **`Vz`** → twin **1/2**  
7. Confirmed web does not quote `2/3` with the 15.5 lb base recipe  
8. Wrote a human prompt anchored on the searchable base recipe (`15.5` pounds…) but asking only for the image-only benzol cell  
9. Live test: model answered **½** from GovInfo OCR → stump succeeded  

### Probe commands that matter

```bash
pdftotext -f N -l N file.pdf - | wc -c          # answer page nearly blank or garbled
pdftotext file.pdf - | grep -n 'ANSWER'         # must be absent
pdftotext file.pdf - | grep -n 'TWIN'           # twin/OCR garble present
pdftoppm -f N -l N -png -r 180 file.pdf page
tesseract page-*.png stdout                     # see what OCR invents
```

Then web-search: `"exact value" + substance + document` → reject if already quoted.

---

## 5. How to write the prompt

### Shape
1. Soft scene (householder / agency / era)
2. Anchors that are searchable (base batch numbers)
3. Natural contrast (this column / this year / this ingredient)
4. Clean ask for the buried cell

### Rules
- 70–150 words
- One atomic answer
- Timeless
- No website names
- No arithmetic
- No em dashes
- Human voice, not “ignore X and Y” recipe tone

### Circ 70 example (worked)

> A householder is mixing white-lead paint on the job for outside work, following an early Bureau of Standards household materials circular. The base batch is 15.5 pounds of white-lead paste, 3 pints of raw linseed oil, and 5 ounces of turpentine Japan drier. For the first coat on yellow pine or cypress, the additions table calls for extra raw linseed oil, turpentine, Japan drier, and benzol. How many pints of benzol does that first-coat yellow pine or cypress column specify to add to the base?

---

## 6. How to write the Golden Trajectory

```
Step 1 - Search: "<query>"
Step 2 - Fetch: <index/DOI> - identify the document
Step 3 - Fetch: <metadata> - confirm identity
Step 4 - Verify: right document
Step 5 - Filter: right table/row/column
Step 6 - Fetch (twin): <PDF> p.X - where searchable wrong value lives
Step 7 - Fetch (answer): <PDF> p.Y - image-only true value
Step 8 - Verify: text search misses answer
Step 9 - Twin: explain the trap
```

Hard rules:
- Every Fetch needs an in-page location
- GT URLs ↔ Verification Sources must match (parity)
- Prefer lead-agency / official hosts
- Never put archive.org in Verification Sources
- 3+ hops

---

## 7. Twin design (the Shopping win’s key)

Best twin is not just “another number nearby.” Ideal twin is:

1. **Produced by bad OCR of the answer cell itself** (`Vz` → `1/2` vs true `2/3`), or  
2. A searchable adjacent value in the same PDF text layer  

That is why Circ 70 beat Differin/Nizoral: the model’s own PDF text layer lied.

---

## 8. What works vs what doesn’t

### Works
- Aleve `5,460` (image-only narrative; hallucinated `174,000`)
- Navajo `22500` (image-only determination; hallucinated `20,200`)
- Glen Canyon `18%` (raster figure; twin `35%` in text)
- Circ 500 `-149.0` (dense table; OCR-misread `-147.4`)
- Circ 70 benzol `2/3` (OCR twin `1/2` / `Vz`)

### Doesn’t
- Searchable SEC HTML
- Clear labeled modern bar charts (vision OCR)
- Famous Apollo/Scribd-OCR’d tables
- Famous FDA Rx-to-OTC packages with clear prose (Differin)
- Clean modern FDA EA numerals (Nizoral)
- Answer restated in next-page searchable prose

---

## 9. Domain hunting map

| Domain | Prefer | Avoid |
|---|---|---|
| Shopping | Old NBS household circ tables; grainy fractions | Modern FDA EA/OtherR clear numbers; bar charts |
| Business | Image-only FDA EA narratives (Aleve) | SEC HTML |
| Legal | Raster EIS figures + agency scans on lead hosts | Volunteer-only mirrors without official copy |
| Sci/Tech | Obscure NBS/NIST table cells | Famous Apollo flight evals |
| Celebrities | Image-only archival money/date scans | Widely reprinted quotes |

---

## 10. Ship checklist

- [ ] Prompt 70–150, humanized, no site names, no em dashes  
- [ ] Atomic answer  
- [ ] Twin documented  
- [ ] Answer absent from whole-PDF text layer  
- [ ] Twin present in text/OCR  
- [ ] Web does not already quote the pairing  
- [ ] Not a clean modern labeled chart  
- [ ] GT has locations on every Fetch  
- [ ] ≥3 verification URLs + parity  
- [ ] No archive.org verification  
- [ ] Live wrong answer recorded when available  

---

## 11. After a live attempt

Always rewrite failure justification from **expected** to **observed**:

- Circ 70: model answered **½** from GovInfo OCR  
- Circ 500: model answered **−147.4**  
- Aleve: model answered **174,000**  

Observed failures are the best proof the stump is real.
