# Exercise 3 — Loan Documents into the Forbearance Template

- **Workflow:** Summarize a loan package, then use that summary to complete a template
- **Documents:** **Forbearance Agreement Template** + loan package (**Business Loan Agreement, Promissory Note, Commercial Guaranty, Recorded Mortgage, Recorded Assignment of Rents**)
- **Estimated time:** 30 minutes
- **Difficulty:** Applied — the team's highest-value workflow

---

## Objective

Use Copilot to read the loan documents, extract the exact facts the **Forbearance template** needs, build a **fill sheet** that maps each template placeholder to its value and source, and draft the recital language — all verified against the source documents.

## What Copilot is doing here

Copilot summarizes each loan document and extracts named data points. You then use those facts to fill the template's bracketed fields (e.g., `NOTE#`, `MATURITY DATE`, `$PAYOFF`). Copilot speeds the reading and assembly; **you verify every figure** against the source before it goes in the agreement.

## Before you start

- [ ] All loan documents and the Forbearance template are in your OneDrive folder.
- [ ] Open them in Word for the web (PDFs can be summarized via the Copilot side pane or by referencing them).

---

## Steps

### Step 1 — Summarize each loan document
Open each loan document and run:
```text
Act as a legal reviewer preparing a forbearance. Summarize this loan document. Identify: borrower legal name and entity type; lender; loan/note number; note date; original principal amount; current maturity date; interest rate terms; collateral and lien position; any guarantors; and recording details (document number, county, state, recording date) if present. Present as a labeled list. If a value is not stated in this document, write "NOT FOUND IN THIS DOCUMENT."
```

### Step 2 — Extract the facts a forbearance needs
```text
I am assembling facts from a loan package (promissory note, business loan agreement, commercial guaranty, mortgage, and assignment of rents) to draft a forbearance agreement. From the open document, extract every data point a forbearance recital would need and present it as a table: Data Point, Value, Source Document, Section/Page. Include note number, note date, principal amount, maturity date, payoff balance, collateral description and address, mortgage recording details, assignment-of-rents recording details, security agreement date, and guarantor names and guaranty date.
```

Repeat for each document and combine the tables.

### Step 3 — Build the template fill sheet
Open the **Forbearance template**, then prompt:
```text
Act as a paralegal completing Old National Bank's Forbearance Agreement template. I will provide the extracted loan facts. Produce a "fill sheet" mapping each bracketed placeholder in the template to its value, formatted as a table: Placeholder (e.g., BORROWER LEGAL NAME, NOTE#, NOTE DATE, NOTE AMOUNT, MATURITY DATE, $PAYOFF, MORTGAGE DATE, RECORDING DATE, DOCUMENT NUMBER, COUNTY OF RECORDING, GUARANTOR NAME, GUARANTY DATE), Value to Insert, Source. For any placeholder I have not supplied a value for, mark it "NEEDS INPUT." Do not invent values.

LOAN FACTS:
[paste the combined facts from Step 2]
```

### Step 4 — Draft the recitals
```text
Using only the loan facts I provided, draft the RECITALS section of a forbearance agreement in the style of the ONB template: describe the note, loan agreement, mortgage, assignment of rents, security agreement, and guaranty; state the payoff balance; and describe the maturity default. Use the defined terms exactly as the template does (the "Note," the "Loan," the "Mortgage," etc.). Leave any unknown figure as a clearly marked blank like ____.
```

### Step 5 — Choose the optional provisions
```text
The ONB forbearance template contains optional [POSSIBLE] provisions (interim financial statements, tax returns, borrowing base certificates, AR/AP aging reports, personal financial statement, appraisal cooperation). Given this fact pattern: [describe the deal], recommend which optional reporting provisions to include and why. Present as a table: Provision, Include? (Yes/No/Discuss), Rationale. This is a drafting suggestion for attorney review.
```

---

## Deliverable

A completed fill sheet, a drafted recitals section, and a recommendation on optional provisions — all ready for attorney review.

## Verify before you rely on it (critical for this exercise)

Loan facts are **high-risk for transcription error**. Check each against the source PDF:

- [ ] Note number, note date, and original principal amount.
- [ ] Maturity date and current payoff balance.
- [ ] Mortgage and assignment-of-rents **document/recording numbers, county, and state**.
- [ ] Borrower legal name, entity type, and all guarantor names.
- [ ] Anything Copilot marked "NEEDS INPUT" or "NOT FOUND" — fill or confirm manually.

## Key takeaways

- The pattern is **extract → fill sheet → verify → draft.**
- Copilot assembles a draft; recording numbers, amounts, and dates are exactly what you must double-check.
- Telling Copilot to mark unknowns ("NEEDS INPUT", "NOT FOUND") prevents it from inventing values.

---

*Next: Exercise 4 — DACA Customer-Edit Review.*
