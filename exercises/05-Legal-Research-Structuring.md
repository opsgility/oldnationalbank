# Exercise 5 — Legal Research Structuring

- **Workflow:** Use Copilot to structure and draft research, then verify against authoritative sources
- **Document:** **Elder & Vulnerable Adult Financial Exploitation** (EFE) job aid
- **Estimated time:** 20 minutes
- **Difficulty:** Applied

---

## Objective

Use Copilot to **organize and accelerate** research work — building a 50-state survey framework, synthesizing verified notes into consistent job-aid language, and framing a discrete legal question — while keeping a clear line between what Copilot drafts and what you must verify.

## What Copilot is doing here (and the boundary)

Copilot is excellent at **structuring** research: building the matrix, drafting the memo skeleton, and turning your verified notes into clean prose. It is **not a legal-research database** — it does not replace authoritative primary sources. Treat every statutory citation, deadline, and "mandated reporter" determination as **draft until you verify it** against an authoritative source. This exercise shows the happy path: Copilot does the scaffolding and the writing; you supply and confirm the law.

## Before you start

- [ ] The EFE job aid is in your OneDrive folder.
- [ ] For Step 2, you can use the sample notes in **assets/EFE-Verified-Notes-SAMPLE.md** (synthetic; in production you would paste your own source-checked notes).

---

## Steps

### Step 1 — Build the 50-state survey framework
```text
Act as a legal research assistant supporting a bank's compliance team. I am updating the "Requirements by State" section of an Elder & Vulnerable Adult Financial Exploitation (EFE) job aid. Build a blank research framework I can populate for all 50 states, as a table with columns: State, Mandated Reporter for Financial Institutions? (Yes/No), Who Must Report, Trigger/Threshold for Reporting, Reporting Agency (APS / law enforcement), Timeframe to Report, Permitted Information-Sharing Exceptions, Statutory Citation, Notes. Do not fill in legal conclusions — produce the empty structure plus a one-line description of what belongs in each column.
```

### Step 2 — Synthesize VERIFIED notes into job-aid language
After you have researched and **confirmed** the law for a state, have Copilot format it:
```text
I will paste verified, source-checked notes on a state's EFE reporting requirements. Convert them into consistent, plain-language entries for our internal job aid, matching this format: State name as a heading; then bullets for Mandated Reporter status, Reporting Agency, Timeframe, and Information-Sharing Exception. Keep wording neutral and operational. Do not add any requirement I did not provide.

VERIFIED NOTES:
[paste your confirmed notes — for this session, paste the block from assets/EFE-Verified-Notes-SAMPLE.md]
```

### Step 3 — Frame a discrete legal question
Example: MLO referral-contest compensation.
```text
Act as a legal research assistant. I need to analyze whether a bank may run a referral contest in which mortgage loan originators (MLOs) earn entries into a prize drawing based on the number of referrals they make for OTHER bank products (not mortgage loans). Produce a research plan, not a legal conclusion: list the issues to investigate, the key questions under each, and the authoritative sources I should check. Flag where federal vs. state analysis may differ.
```

### Step 4 — Draft a memo skeleton
```text
Create a legal research memo outline on this question: [state the question]. Use this structure: Question Presented; Short Answer (leave blank for me to complete after research); Facts/Assumptions; Discussion (with sub-headings per legal issue); and Open Items / Verification Needed. Populate the Discussion sub-headings based on the issues, but leave conclusions for me to write after verifying sources.
```

---

## Deliverable

A populated-structure 50-state matrix (ready for you to fill with verified law), a research plan for the discrete question, and a memo skeleton.

## Verify before you rely on it (non-negotiable)

- [ ] **Every** statutory citation is confirmed against an authoritative source.
- [ ] Reporting timeframes and mandated-reporter determinations are current.
- [ ] No "fact" in the output originated from Copilot rather than a source you checked.

## Key takeaways

- Copilot **scaffolds and writes**; it does not supply the law.
- Use it for the matrix, the skeleton, and the formatting — then verify.
- Asking Copilot to *leave conclusions blank* keeps the legal judgment with you.

---

*This is the final exercise. Return to the deck summary for the recommended reusable workflow.*
