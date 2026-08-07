# Business — Staples/Office Depot FTC demonstrative: W.B. Mason win-loss appearances

**Answer:** `132`  
**Famous twin:** `833` — same-page chart title (“Staples Dominates in Office Depot’s Win-Loss Data with 833 Appearances”), which matches the tallest bar (Staples).

---

## Prompt (72 words)

In the Federal Trade Commission’s 2016 federal district-court challenge to Staples’ proposed acquisition of Office Depot, economist Carl Shapiro’s redacted public demonstrative exhibit PX06500 includes a bar chart of competitor appearances in Office Depot’s consumable-office-supplies win-loss data for 2013 through 2015, drawn from a sample of 1,253 observations and sourced to Exhibit 10 of the Shapiro Report. For the regional supplier W.B. Mason, what exact number of appearances does that chart show?

---

## Answer

`132`

---

## Golden Trajectory

**Step 1 — Search:** `FTC Staples Office Depot Shapiro demonstrative PX06500 win-loss`

**Step 2 — Fetch:** FTC case materials / docket references identifying Carl Shapiro’s demonstrative presentation used with his direct testimony in *FTC v. Staples / Office Depot* (D.D.C. 2015–2016). Confirms the exhibit exists; does **not** state W.B. Mason’s appearance count.

**Step 3 — Fetch:** https://www.ftc.gov/system/files/documents/cases/170216staples_redacted_shapiro_demonstrative.pdf — **PDF page 4** (PX06500-004): title *“Staples Dominates in Office Depot’s Win-Loss Data with 833 Appearances”*; subtitle *2013–2015 (N = 1253)*; source Exhibit 10, Shapiro Report.

**Step 4 — Verify:** Document is the redacted public Shapiro demonstrative (82 pages); page matches the win-loss appearances chart described in the prompt.

**Step 5 — Filter:** Fixes which exhibit page and that the question is about the **appearances** chart (not the adjacent “240 Wins” chart on page 5).

**Step 6 — Fetch:** same PDF — **PDF page 4 / printed page 4 / PX06500-004**. The bar chart is a **raster** graphic (chart labels have no text layer). Bar labels read: Staples = **833**; W.B. Mason = **132**; XPEDX/Veritiv = **33**; then Complete Office **9**, Grainger **7**, Office360 **6**, and several competitors at **5**.

**Step 7 — Verify:** The W.B. Mason bar reads **132**.

**Step 8 — Calibrate (internal check):** The searchable title on the same page states Staples has **833** appearances, and the tallest bar is labeled **833**—confirming the bar scale/labels are read correctly—so the second bar’s **132** (W.B. Mason) is trustworthy.

**Step 9 — Confirm the twin:** Full-text search of the PDF surfaces the title-text **833** and does **not** return **132**, because the bar values (other than the title’s restatement of Staples’ 833) live only in the raster chart image.

---

## Verification Sources

1. https://www.ftc.gov/system/files/documents/cases/170216staples_redacted_shapiro_demonstrative.pdf — PDF page 4 / PX06500-004 (W.B. Mason = 132; twin title 833 Appearances).  
2. FTC *Staples/Office Depot* litigation docket (D.D.C. No. 1:15-cv-02115) — identifies PX06500 as Shapiro’s demonstrative.

---

## Shell proof (verified)

```text
$ pdftotext -f 4 -l 4 staples_demo.pdf -
# → title/note/source only; no "132", no "W.B. Mason"

$ rg -n '132' <(pdftotext staples_demo.pdf -) || echo '132 ABSENT'
# → PASS: 132 ABSENT from entire PDF text layer

$ rg -n '833' <(pdftotext staples_demo.pdf -)
# → "with 833 Appearances" (twin present in text layer)

$ pdftoppm -f 4 -l 4 -png -r 200 … && tesseract … stdout
# → OCR reads bar labels: 833 (Staples), 132 (W.B. Mason), …
```

---

## Checklist

| Ask | Resolution |
|---|---|
| Answer only in raster chart | Bar labels are image-only; `pdftotext` misses **132** on page 4 and in the full PDF |
| Famous/easy twin in searchable text | Same-page title **833 Appearances** matches the Staples bar |
| Calibrate then read harder bar | **833** calibrates the first bar → second bar **132** |
| Not Illumina-GRAIL $315M | Different case, different metric |
| No archive.org | FTC.gov PDF |
| Atomic / no arithmetic | Single integer appearance count |
