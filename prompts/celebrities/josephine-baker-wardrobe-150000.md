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
**Step 1 — Fetch:** https://en.wikipedia.org/wiki/Josephine_Baker — in the civil-rights / early-1950s U.S. material, the October 1951 Stork Club write-up.  
**Step 1 — Verify:** That’s Baker — American-born, based in France, the singer who said the Stork Club wouldn’t serve her.  
**Step 1 — Filter:** Name is settled; still nothing on what the invitation said the wardrobe was worth.

**Step 2 — Search:** `"Josephine Baker" "National Council of Negro Women" "National Guard Armory" 1951`  
**Step 2 — Fetch:** https://en.wikipedia.org/wiki/Josephine_Baker — same page, early-1950s U.S. appearances / activism.  
**Step 2 — Verify:** Fits the Washington / NCNW booking the prompt describes.  
**Step 2 — Filter:** Still no dollar figure for the wardrobe on that invitation.

**Step 3 — Search:** `"Josephine Baker" "$250,000" wardrobe OR "250,000 Wardrobe" Jet 1951`  
**Step 3 — Fetch:** https://www.flickr.com/photos/vieilles_annonces/3202349851 — scan/caption of *Jet*, November 29, 1951, “Josephine Baker and Her $250,000 Wardrobe.”  
**Step 3 — Verify:** Press from that tour really did call the wardrobe $250,000 — easy to grab, but it’s *Jet* in November, not the June invitation.  
**Step 3 — Filter:** Set $250,000 aside; need the actual letter.

**Step 4 — Search:** `"Josephine Baker" FBI file OR "FBI Files" wardrobe OR "National Council of Negro Women" invitation Hoover`  
**Step 4 — Fetch:** https://archive.org/details/JosephineBakerFBI — *Josephine Baker FBI Files*; open `jbaker2a.pdf`.  
**Step 4 — Verify:** FOIPA release of scanned pages (image PDF, basically no text layer), including 1951 correspondence.  
**Step 4 — Filter:** Work from the scans, not the magazine roundup.

**Step 5 — Fetch:** https://archive.org/download/JosephineBakerFBI/jbaker2a.pdf — **page 88**. Letter dated June 19, 1951, Dorothy B. Ferebee (National Council of Negro Women) to J. Edgar Hoover, plugging the July 2 National Guard Armory show. Mid-letter: *“Miss Baker will display her famous wardrobe valued at $150,000.00 — the finest creations of the French fashion makers.”* Bureau stamp near the bottom (recorded July 1951; serial around `100-348501-18`).  
**Step 5 — Verify:** That’s the number the invitation actually used.  
**Step 5 — Filter:** Answer is `$150,000` (or `$150,000.00`); the Jet `$250,000` is a different source.

**Final check:** *Jet* (Nov. 29, 1951) went with $250,000 for the tour wardrobe. The June 19 NCNW invite in the FBI file says $150,000.00. Wikipedia never quotes that letter figure.

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
