# Exercise 1 — Contract Review & Summarization

- **Workflow:** Read a contract fast and accurately with Copilot in Word
- **Document:** **Consulting Services Agreement (SAMPLE).docx**
- **Estimated time:** 20 minutes
- **Difficulty:** Foundational — do this one first

---

## Objective

Build the core habit every other exercise depends on: before you edit anything, use Copilot to **summarize** the agreement, **extract its obligations**, and **generate an issue-spotting checklist**. By the end you will have a one-page reviewer brief you produced in minutes instead of an hour.

## Before you start

- [ ] **Consulting Services Agreement (SAMPLE).docx** is in your **Copilot Legal Session** OneDrive folder (see pre-work).
- [ ] Open it in **Word for the web**.
- [ ] Confirm the **Copilot** button appears on the Home ribbon.

## What Copilot is doing here

Copilot reads the **open document** and answers grounded in its text. This is the strongest, lowest-risk use of Copilot for legal work: summarizing and locating information that is already in front of you. You stay the reviewer; Copilot just reads faster.

---

## Steps

### Step 1 — Open Copilot in the document
Open the **Consulting Agreement** in Word for the web, then click **Copilot** on the Home ribbon to open the side pane.

### Step 2 — Summarize for a legal reviewer
Paste this prompt into the Copilot pane:

```text
Act as a legal reviewer at a bank. Summarize this agreement for an attorney who has not read it. Cover, in this order: parties and their roles; effective date and term; key obligations of each party; fees and payment terms; termination rights and notice periods; intellectual property ownership; confidentiality; indemnification; limitation of liability; and governing law. Keep it under 400 words and flag anything ambiguous or missing.
```

**Expected result:** a structured summary that follows your requested order. Note how naming the *role* ("legal reviewer at a bank") and the *output shape* ("under 400 words", specific order) produces a far more useful answer than "summarize this."

### Step 3 — Extract obligations and deadlines
```text
Extract every obligation, deadline, and renewal or notice trigger in this agreement. Present as a table with columns: Obligation, Responsible Party, Trigger/Deadline, Section Reference. List dates explicitly. If a deadline is relative (e.g., "30 days after termination"), state the trigger.
```

**Expected result:** a table you can scan for the dates and duties that matter.

### Step 4 — Generate an issue-spotting checklist
```text
Act as outside counsel performing a first-pass review. Produce a checklist of clauses a reviewer should examine closely, with a one-line reason for each. Focus on terms that are commonly negotiated or that allocate risk: indemnity, limitation of liability, IP assignment, confidentiality scope, termination for convenience, auto-renewal, assignment, and dispute resolution. Note any standard protective clause that appears to be MISSING.
```

Continue the conversation:

```
Turn this into a redline-ready issue list with a proposed fallback position for each clause.
```

### Step 5 — Drill into one clause (optional)
Pick a clause the checklist flagged and ask:
```text
Explain the [limitation of liability] clause in this agreement in plain language for a business stakeholder who is not a lawyer. State what it means, who it favors, and the practical consequence if something goes wrong. Do not change the document.
```

---

## Deliverable

A short reviewer brief containing (1) the summary, (2) the obligations table, and (3) the issue checklist. Copy Copilot's responses into a new Word doc or a Copilot Page.

## Verify before you rely on it

Copilot is reading your document, but **spot-check** these every time:

- [ ] Party names and the effective date match the document.
- [ ] Dollar figures and dates in the obligations table are correct.
- [ ] Any clause Copilot says is "missing" really is missing (search the document to confirm).

## Key takeaways

- Summarize **before** you edit — it orients your review.
- **Role + specificity + output shape** is what separates an expert prompt from a basic one (this is the prompt-engineering module in practice).
- Copilot accelerates reading; the lawyer still decides what matters.

---

*Next: Exercise 2 — Market-Standard Assessment & Redlining.*
