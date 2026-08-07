# Business — Illumina–GRAIL continuation-payment equity threshold

**Answer:** `$315,000,000`  
**Famous twin:** `$300,000,000` (reverse termination fee / matching preferred-stock investment in the same agreement). Secondary traps: `$35,000,000` (monthly continuation payment), `$8 billion` (headline deal value), `$476 million` (EU gun-jumping fine).

---

## Prompt (112 words)

In September 2020, a San Diego DNA-sequencing company announced a cash-and-stock deal to reacquire a multi-cancer blood-test developer it had previously spun out—a transaction later described as worth about eight billion dollars and completed over active U.S. and European antitrust objections. Their merger agreement required the buyer, if closing slipped past a mid-December 2020 date, to make fixed monthly cash “continuation” payments to the target until close or termination. Under that same agreement, if the deal later terminated, the buyer would receive non-voting preferred stock of the target covering continuation payments above what exact dollar threshold?

---

## Answer

`$315,000,000`

---

## Golden Trajectory

**Step 1 — Search:** `"Illumina" "GRAIL" "8 billion" OR "$8 billion" 2020 acquire OR acquisition`  
**Step 1 — Fetch:** https://en.wikipedia.org/wiki/Illumina,_Inc. — **History** section, paragraph on the September 2020 proposed cash-and-stock deal to acquire GRAIL for `$8 billion` (IDs buyer/target).

**Step 2 — Search:** `"Illumina" "GRAIL" "termination fee" OR "Continuation Payments" OR "$300 million" 2020`  
**Step 2 — Fetch:** https://www.sec.gov/Archives/edgar/data/1110803/000095015720001122/form425.htm — Form 8-K / Form 425 filed for Illumina (event date Sept. 20, 2020), **Item 1.01 Entry into a Material Definitive Agreement**, paragraph on Continuation Payments: monthly `$35 million` and preferred stock for amounts **in excess of `$315 million`**; nearby text also states the `$300 million` termination fee (the twin — reject as the equity threshold).

**Step 3 — Search:** `"Continuation Payments in excess of $315,000,000" Illumina GRAIL`  
**Step 3 — Fetch:** https://www.sec.gov/Archives/edgar/data/1110803/000119312520302773/d801214ds4.htm — Illumina/GRAIL S-4 consent solicitation statement/prospectus, **QUESTIONS AND ANSWERS** section, question **“What happens if the Transaction is not completed?”** (**prospectus page 8**): *“Illumina will receive shares of non-voting GRAIL preferred stock in respect of all Continuation Payments in excess of $315,000,000.”*

**Step 4 — Fetch (confirm twin in same Q&A):** same S-4 URL — same **page 8** Q&A paragraph opens with the `$300,000,000` termination fee / additional `$300,000,000` preferred investment — different figure from the `$315,000,000` continuation threshold.

---

## Verification Sources

1. https://www.sec.gov/Archives/edgar/data/1110803/000119312520302773/d801214ds4.htm — S-4, Q&A “What happens if the Transaction is not completed?”, prospectus page 8; `$315,000,000`.  
2. https://www.sec.gov/Archives/edgar/data/1110803/000095015720001122/form425.htm — Item 1.01; `$315 million` continuation threshold + `$300 million` twin.  
3. https://en.wikipedia.org/wiki/Illumina,_Inc. — History section; `$8 billion` GRAIL deal ID.

---

## Checklist

- [x] One answer only — threshold bound to continuation-payment equity conversion  
- [x] Timeless — Sept. 2020 merger agreement (finished event)  
- [x] Question, not recipe — no website/doc names in prompt  
- [x] 3+ source hops — wiki ID → 8-K/425 twin → S-4 page 8  
- [x] No arithmetic  
- [x] Atomic answer — `$315,000,000`  
- [x] In-page locations on every Fetch  
- [x] No archive.org verification links  

---

## Why it should stump

Model latches onto the same-paragraph **`$300,000,000`** termination fee (or `$8B` / `$35M` / `$476M` EU fine) from press and skims past the quieter **`$315,000,000`** “Continuation Payments in excess of…” equity threshold that only the merger docs state cleanly.
