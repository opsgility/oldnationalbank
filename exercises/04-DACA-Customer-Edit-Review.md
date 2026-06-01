# Exercise 4 — DACA Customer-Edit Review

- **Workflow:** Triage customer redlines, then route questions with Word's collaboration tools
- **Document:** **DACA Agreement** (Deposit Account Control Agreement) with customer edits
- **Estimated time:** 20 minutes
- **Difficulty:** Applied

---

## Objective

A customer returned edits to ONB's standardized DACA. Use Copilot to compare the edited version to the bank's standard position, **triage each change** (accept / negotiate / reject), draft a response, and a question list — then use Word's **comments and @mentions** (a human step) to route open questions to the right partners.

## What Copilot is doing here

Copilot compares versions and drafts analysis. It **cannot** add or modify Word comments, and it does not route work to people — comments, @mentions, and assignments are done by you. Copilot drafts the *text*; a person places it.

## Before you start

- [ ] DACA Agreement (with customer edits) is in your OneDrive folder.
- [ ] Have ONB's standard DACA position available to reference.

---

## Steps

### Step 1 — Triage the redlines
Open the edited DACA and run:
```text
Act as a banking attorney reviewing customer edits to Old National Bank's standard Deposit Account Control Agreement (with activation). Compare the edited language to the bank's standard position. For each material change, produce a table: Section, Customer's Change (short quote), Effect on the Bank, Risk Level (High/Medium/Low), Recommendation (Accept / Negotiate / Reject), Suggested Response Language. Pay special attention to: the bank's control rights, the notice of exclusive control, the bank's limited liability, indemnification, subordination/setoff, charge-back obligations, termination, and governing law/jury-trial waiver.
```

### Step 2 — Build the sign-off summary
```text
Summarize the customer's DACA edits into three buckets for an approval discussion: (1) Acceptable as drafted, (2) Acceptable with modification, (3) Not acceptable / must revert. Under each, list the sections and a one-line reason. Keep it to a single page.
```

### Step 3 — Generate the reviewer question list
```text
Create a list of questions I should resolve before responding to the customer on these DACA edits. Group them by: control and access rights, bank liability and indemnification, fees and charge-backs, operational feasibility for the deposit-operations team, and legal/governing-law.
```

### Step 4 — Route the questions (human collaboration step)
Now switch to Word's review tools:
1. Select the relevant clause → **Review → New Comment**.
2. Paste a question from Step 3 into the comment.
3. Type **@** and the colleague's name to **@mention** a partner (e.g., deposit operations or a risk reviewer) and assign it.

> Copilot drafted the questions; **you** place the comments and @mention people. That separation keeps a clear record of human judgment.

### Step 5 — Draft the response to counsel
```text
Draft a professional, concise email to the customer's counsel responding to their DACA edits. For each change we accept, confirm briefly. For each we cannot accept, explain the bank's position in one or two sentences and propose fallback language where appropriate. Maintain a collaborative, non-adversarial tone. Mark anything that still needs internal approval as "[PENDING INTERNAL REVIEW]."
```

---

## Deliverable

A triage table, a one-page sign-off summary, comments/@mentions placed in the document for open questions, and a draft response to counsel.

## Verify before you rely on it

- [ ] Each customer change Copilot flagged actually appears in the document.
- [ ] Risk ratings reflect ONB's real position — adjust where your judgment differs.
- [ ] The draft email contains no commitment that has not been internally approved.

## Key takeaways

- Copilot **triages and drafts**; you **decide and route**.
- Comments and @mentions are a **human collaboration layer** Copilot does not touch.
- A clean accept / negotiate / reject table turns a messy redline into a fast approval conversation.

---

*Next: Exercise 5 — Legal Research Structuring.*
