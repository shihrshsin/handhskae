# Celebrities / Public Figures — Josephine Baker wardrobe valuation

**Niche figure:** Josephine Baker  
**Answer:** `$150,000`  
**Famous twin (model trap):** `$250,000` — *Jet* (Nov. 29, 1951) headline/feature “Josephine Baker and Her $250,000 Wardrobe” (also repeated in 1951 U.S. tour accounts: ~45 trunks / $250,000 in costumes). Secondary traps: `$10,000` (Miami segregated-audience fee) and the 1960 Montreal “~$10,000 stolen clothing” wire figure.

---

## Prompt (89 words)

In mid-1951, an American-born French cabaret star—who the previous October had publicly accused New York's Stork Club of refusing to serve her—was presented in Washington, D.C., by the National Council of Negro Women at the National Guard Armory. The council president's invitation letter promoting that Monday, July 2 concert promised that, in addition to a rare evening of music and exotic dancing, she would display her famous wardrobe of the finest creations of the French fashion makers. What exact dollar valuation did that invitation letter assign to the wardrobe?

---

## Answer

`$150,000`

---

## Golden Trajectory

**Step 1 — Search:** `"Stork Club" "Josephine Baker" 1951 refused OR discrimination`  
**Step 1 — Fetch:** https://en.wikipedia.org/wiki/Josephine_Baker — Civil rights / 1950s U.S. section; paragraph on the October 1951 Stork Club incident identifying the star as Josephine Baker.  
**Step 1 — Verify:** Confirms the American-born French cabaret star tied to the Stork Club refusal is Josephine Baker.  
**Step 1 — Filter:** Locks the subject; does not yet give the wardrobe dollar figure.

**Step 2 — Search:** `"Josephine Baker" "National Council of Negro Women" "National Guard Armory" 1951`  
**Step 2 — Fetch:** https://en.wikipedia.org/wiki/Josephine_Baker — same biography; Civil rights activism paragraphs covering her early-1950s U.S. appearances and activism (no wardrobe valuation stated).  
**Step 2 — Verify:** Places Baker in the NCNW / Washington performance context of the prompt.  
**Step 2 — Filter:** Narrows to mid-1951 Washington promotion materials; still no `$150,000`.

**Step 3 — Search:** `"Josephine Baker" "$250,000" wardrobe OR "250,000 Wardrobe" Jet 1951`  
**Step 3 — Fetch:** https://www.flickr.com/photos/vieilles_annonces/3202349851 — Flickr scan/caption of *Jet*, November 29, 1951, “Josephine Baker and Her $250,000 Wardrobe.”  
**Step 3 — Verify:** Surfaces the famous contemporary press twin (`$250,000`) for Baker’s 1951 tour wardrobe — **not** the dollar figure printed on the June 19 NCNW invitation.  
**Step 3 — Filter:** Rejects the Jet tour figure; forces retrieval of the actual invitation letter.

**Step 4 — Search:** `"Josephine Baker" FBI file OR "FBI Files" wardrobe OR "National Council of Negro Women" invitation Hoover`  
**Step 4 — Fetch:** https://archive.org/details/JosephineBakerFBI — item *Josephine Baker FBI Files*; open part `jbaker2a.pdf`.  
**Step 4 — Verify:** Confirms an image-only FOIPA scan set (1999 Acrobat PDFWriter; no usable text layer) holding mid-1951 correspondence.  
**Step 4 — Filter:** Points to the scanned FBI holdings rather than press summaries.

**Step 5 — Fetch:** https://archive.org/download/JosephineBakerFBI/jbaker2a.pdf — **PDF page 88** (letter dated June 19, 1951, from Dorothy B. Ferebee, President, National Council of Negro Women, Inc., to Mr. J. Edgar Hoover). Body paragraph beginning “In addition to a rare evening of music and exotic dancing…” states: **“Miss Baker will display her famous wardrobe valued at $150,000.00 — the finest creations of the French fashion makers.”** File stamp / serial near foot: recorded July 1951, serial path consistent with `100-348501-18`.  
**Step 5 — Verify:** Reads the exact wardrobe valuation required by the prompt.  
**Step 5 — Filter:** Accepts `$150,000` (equivalently `$150,000.00`) and rejects the Jet `$250,000` twin.

**Final confirmation:** Contemporary 1951 press (*Jet*, Nov. 29) widely pegs Baker’s wardrobe at `$250,000`. The NCNW invitation of June 19, 1951 — preserved as an image-only page in the FBI FOIPA set — assigns `$150,000.00` instead. That letter figure is not restated on her Wikipedia biography.

---

## Verification Sources

1. https://archive.org/download/JosephineBakerFBI/jbaker2a.pdf — PDF page 88, June 19, 1951 NCNW invitation letter (Ferebee → Hoover); wardrobe sentence with `$150,000.00`.  
2. https://archive.org/details/JosephineBakerFBI — parent FOIPA release / item page for the Josephine Baker FBI Files.  
3. https://en.wikipedia.org/wiki/Josephine_Baker — Stork Club (1951) identification of the star.  
4. https://www.flickr.com/photos/vieilles_annonces/3202349851 — *Jet*, Nov. 29, 1951, “Josephine Baker and Her $250,000 Wardrobe” (famous twin the model substituted).

---

## Why this should stump (failure modes)

| Model failure | Why it happens |
|---|---|
| Answers `$250,000` (**observed**) | Substitutes *Jet*’s Nov. 29, 1951 “$250,000 Wardrobe” tour figure / 45-trunk accounts for the June 19 invitation’s `$150,000` |
| Answers `$10,000` | Substitutes the famous Miami club fee from Wikipedia / bios |
| Answers `$3,000,000` / `$3 million` | Confuses with Jet’s later “estate may exceed $3 million” line |
| Answers `$10,000` (clothing) | Confuses with 1960 Montreal UPI “~$10,000 stolen clothing and music” charge also present in the same FBI set |
| Gives ticket prices (`$6.00` etc.) | Reads nearby dollar figures on the same letter if partially OCR’d |
| Abstains / “not publicly stated” | Letter valuation is not on Wikipedia; PDF is image-only and not usefully full-text indexed |

---

## Checklist

- [x] One atomic answer (`$150,000`)
- [x] Superlative/measure bound (exact dollar valuation on the named invitation)
- [x] Timeless (1951 concert; no “currently”)
- [x] Question, not recipe (no website/doc names in the prompt)
- [x] 3+ source hops (wiki ID → twin reject → FBI item → page 88)
- [x] No arithmetic
- [x] Every Verification Source URL appears in the Golden Trajectory
- [x] Exact in-page location (PDF page 88; letter date; quoted sentence)
- [x] Quoted exact search queries on Search steps
- [x] Not a copy of the four official examples
