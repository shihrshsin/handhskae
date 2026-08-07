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
**Step 1 — Fetch:** https://en.wikipedia.org/wiki/Josephine_Baker — Stork Club, Oct 1951.  
**Step 1 — Verify:** That’s the star — Josephine Baker.  
**Step 1 — Filter:** Name locked; no wardrobe dollar yet.

**Step 2 — Search:** `"Josephine Baker" "National Council of Negro Women" "National Guard Armory" 1951`  
**Step 2 — Fetch:** https://en.wikipedia.org/wiki/Josephine_Baker — same bio, early-1950s U.S. / Washington context.  
**Step 2 — Verify:** Fits the NCNW / National Guard Armory booking.  
**Step 2 — Filter:** Still no wardrobe dollar on the invitation.

**Step 3 — Search:** `"Josephine Baker" wardrobe valued OR "wardrobe valued at" OR "$10,000" Miami`  
**Step 3 — Fetch:** https://en.wikipedia.org/wiki/Josephine_Baker — the `$10,000` Miami club fee.  
**Step 3 — Verify:** Famous public dollar, but it’s the Miami fee, not the invitation’s wardrobe figure.  
**Step 3 — Filter:** Reject `$10,000`; need the letter itself.

**Step 4 — Search:** `"Josephine Baker" FBI file OR "FBI Files" wardrobe`  
**Step 4 — Fetch:** https://archive.org/details/JosephineBakerFBI — open `jbaker2a.pdf`.  
**Step 4 — Verify:** FOIPA scan set with mid-1951 correspondence.  
**Step 4 — Filter:** Go to the PDF, not press summaries.

**Step 5 — Fetch:** https://archive.org/download/JosephineBakerFBI/jbaker2a.pdf — **PDF page 88**, June 19, 1951 letter (Dorothy B. Ferebee → Hoover): *“Miss Baker will display her famous wardrobe valued at $150,000.00.”*  
**Step 5 — Verify:** That’s the invitation’s wardrobe valuation.  
**Step 5 — Filter:** Answer `$150,000`; not the Miami `$10,000`.

**Step 6 — Search:** `"Josephine Baker" site:vault.fbi.gov`  
**Step 6 — Fetch:** https://vault.fbi.gov/josephine-baker — open Part 02.  
**Step 6 — Fetch:** https://vault.fbi.gov/josephine-baker/Josephine%20Baker%20Part%2002/at_download/file — **PDF page 176**, same June 19, 1951 Ferebee letter; same line: wardrobe valued at `$150,000.00`.  
**Step 6 — Verify:** Vault copy matches the archive.org page-88 letter.  
**Step 6 — Filter:** Confirms `$150,000` on an allowed non–archive.org host.

**Final check:** Wiki pushes `$10,000` (Miami). The June 19 NCNW invite says `$150,000.00` — `jbaker2a.pdf` p.88 and Vault Part 02 p.176.

---

## Verification Sources

1. https://vault.fbi.gov/josephine-baker/Josephine%20Baker%20Part%2002/at_download/file — PDF page 176; June 19, 1951 NCNW letter; `$150,000.00`.  
2. https://vault.fbi.gov/josephine-baker — Vault subject page (Part 02).  
3. https://en.wikipedia.org/wiki/Josephine_Baker — IDs Baker; Miami `$10,000` twin.

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
- [x] 3+ source hops (wiki ID → Miami twin reject → archive.org letter → Vault confirm)
- [x] No arithmetic
- [x] Every Verification Source URL appears in the Golden Trajectory
- [x] Exact in-page location (`jbaker2a.pdf` p.88 / Vault Part 02 p.176; quoted sentence)
- [x] No archive.org links in Verification Sources (Vault used instead)
- [x] Quoted exact search queries on Search steps
- [x] Not a copy of the four official examples
