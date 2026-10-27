# Ubuntu Digital Bank: GRC Risk Register

A beginner GRC portfolio project. I built a risk register for a **fictional** South African digital bank to practise identifying, scoring, testing and tracking risks the way it's done in banking.

>  Everything here is fictional and for learning only. The bank, risks, scores, controls, owners, dates and test results are illustrative assumptions. This is not a real audit, regulatory assessment or legal opinion, and no real customer or employer data was used.

## What's in the workbook

`Ubuntu_Digital_Bank_GRC_Risk_Register_FINAL.xlsx` has seven sheets:

| Sheet | What it covers |
|---|---|
| Risk Register | 11 banking and IT risks with inherent and residual scoring, controls, treatment, owner and status |
| Read Me | Project purpose, limitations and plain-English column definitions |
| Scoring Guide | The 5x5 likelihood and impact scales and the risk bands |
| Project Notes | Objective, scope, method and ethics |
| Control Test Evidence | Simulated control tests with initial results, retests and limitations |
| Action Tracker | Actions with owners, completion evidence and closure rules |
| Final Project Summary | Conclusions, governance and limitations |

## Method

1. Identify risks across cyber, availability, data protection, access, change, third-party, fraud, backup, people, compliance and governance.
2. Score likelihood and impact from 1 to 5. Inherent score = likelihood x impact, before controls.
3. Assess whether existing controls actually work, without assuming they do.
4. Estimate residual risk after controls.
5. Define treatment, owner, target date and the evidence needed to close each action.

Risk bands used: 1 to 5 Low, 6 to 11 Medium, 12 to 19 High, 20 to 25 Critical.

## Deeper dives

Two risks got a fuller assessment:

- **R-001 Customer account takeover** (inherent 20 Critical, residual 15 High). Simulated tests on login monitoring (18/20 then 20/20 after rule updates), account recovery (3/4 then 4/4) and a phishing simulation (100 staff, 20 clicked, 5 entered credentials, 10 reported). Monitoring and recovery improved, but phishing awareness is still only partial, so the residual risk stays High pending authorised review.
- **R-011 Inconsistent evidence retention** (residual 12 High). Similar gaps in three departments, so I treated it as one bank-wide risk with department-level actions. A successful retest can't recreate evidence that was already lost, which is why the fix is a central policy, repository and periodic checks.

## Top risks

See `Top_Risks_Summary.pdf` for a one-page view.

## What I'd do next

- Add a written rationale for every score
- Separate verified controls from assumed ones
- Add evidence references for the nine risks that are still illustrative
- Validate scores with stakeholders in a real setting

## Skills practised

Risk assessment, inherent vs residual risk, control effectiveness, control testing, treatment planning, risk ownership, evidence and auditability, banking context.

## Author

Siyabonga Msengana
