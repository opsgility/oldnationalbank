# Exercise 2 — Market-Standard Assessment & Redlining

- **Workflow:** Compare language to a standard you provide, then redline with Track Changes
- **Documents:** **Consulting Services Agreement (SAMPLE).docx** + **Mutual Non-Disclosure Agreement (SAMPLE).docx**
- **Estimated time:** 25 minutes
- **Difficulty:** Core skill

---

## Objective

Use Copilot to assess contract language against **a standard position you supply** (your playbook, a preferred-form clause, or ONB's standard language), generate tiered fallback options, and produce the revisions as **tracked changes** you control.

<!--## Important: how "market-standard" actually works

Copilot does not have a built-in database of market norms. It compares the document to **whatever reference you give it.** So the expert technique is to **ground the comparison**: paste your standard clause or playbook position into the prompt, or have your preferred-form document open. Copilot then tells you how the draft deviates from *your* standard. This is the accurate, reliable way to do a "market-standard" review with Copilot.-->

## Before you start

- [ ] **Consulting Services Agreement (SAMPLE).docx** and **Mutual Non-Disclosure Agreement (SAMPLE).docx** are in your OneDrive folder.
- [ ] Have your **standard/preferred language** ready to paste. For this session, use the **Standard Clause Playbook (SAMPLE)** — copy the relevant clause block from it into the `OUR STANDARD:` part of each prompt. (In production, you would paste ONB's real playbook language instead.)

---

## Steps

### Step 1 — Turn ON Track Changes (manually) FIRST
On the **Review** tab, turn **Track Changes ON** *before* you ask Copilot to edit.

> **Why first:** When Track Changes is already on, Edit-with-Copilot edits are captured as tracked changes you can accept or reject. Copilot **cannot** turn tracking on or off, and it **cannot** accept or reject changes — that is your job. Turn it on yourself, every time.

### Step 2 — Assess against your standard
Open Copilot in the Consulting Agreement and paste:

```text
Act as a commercial contracts attorney. I will paste our standard position below. Compare this agreement's [limitation of liability and indemnification] clauses to our standard and identify every deviation. Present a table with columns: Clause, Current Language (short quote), Our Standard, Deviation, Why It Matters, Suggested Direction.

OUR STANDARD:
[paste the Fees/Payment, Indemnification, and Limitation of Liability blocks from the Standard Clause Playbook (SAMPLE)]
```

**Expected result:** a deviation table measured against *your* language, not a generic guess. (The sample agreement was written with several off-market terms, so this should surface real hits — a one-month liability cap, a one-way client indemnity, a 5%/month late charge, and more.)

### Step 3 — Generate tiered fallback language
```text
Suggest alternative language for the [indemnification] clause. Provide three options labeled Conservative (most protective of the bank), Balanced (likely acceptable to both sides), and Aggressive (most favorable to the counterparty). For each, give the proposed clause text and a one-sentence note on the trade-off.
```

### Step 4 — Make a tracked edit with Edit-with-Copilot
With Track Changes still ON, select the clause in the document, use **Edit with Copilot**, and prompt:
```text
Rewrite the [limitation of liability] clause to be more favorable to the bank while keeping the tone professional and commercially reasonable. Preserve defined terms exactly as they appear elsewhere in the document.
```
**Question**: *What do you need to insert the changes into the document?*

The edit appears as a **tracked change**. Review it, then **Done or Undo** each change yourself.

### Step 5 — Document the rationale
```text
For the changes just proposed, explain what changed and why the new wording reduces the bank's risk. Present as a short bullet list mapping each change to the risk it addresses, so I can paste it into a note to the business owner.
```

### Step 6 — Repeat on the NDA
```text
Act as a legal reviewer. Analyze this NDA's definition of "Confidential Information," the permitted-use clause, the term/survival period, and the return-or-destruction obligation. Compare each to our standard mutual-NDA position (pasted below) and suggest balanced revisions.

OUR STANDARD:
[paste the NDA blocks (N1 Definition, N2 Exclusions, N4 Term & Survival, N5 Residuals) from the Standard Clause Playbook (SAMPLE)]
```

### Step 7 — See version history in action
Because the file is in OneDrive, open **File → Info → Version history** and note that your pre-edit version is preserved. You can always restore the original language.

---

## Deliverable

A redlined Consulting Agreement (tracked changes) plus a short rationale note, and a list of suggested NDA revisions.

## Verify before you rely on it

- [ ] Every tracked change is one you reviewed and chose to accept/reject.
- [ ] Defined terms were preserved (Copilot sometimes renames them).
- [ ] Fallback language does not introduce a term that conflicts with another clause.

## Key takeaways

- **Ground the comparison** with your own standard — that is what makes "market-standard" review reliable.
- **Track Changes goes on manually, first.** Copilot edits within it; you accept/reject.
- OneDrive version history is your safety net for original language.

---

*Next: Exercise 3 — Loan Documents into the Forbearance Template.*
