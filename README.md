# The Full Slice — Commitment Preview

> **An independent product teardown and prototype exploring how Slice can make future repayment commitments more visible within its Slice-in-3 journey.**

## Demo Link - [Live Prototype](https://dishagupta121.github.io/Slice-commitment-preview/)

---

## The Problem

Slice has made credit feel increasingly simple and immediate through its UPI-native payment experience and Slice-in-3. But while the purchase happens instantly, the repayment commitment extends beyond that moment.

The challenge is not necessarily understanding the purchase amount, but understanding **what the user is committing to after today** before confirming the split.

### Product Opportunity

**How might Slice make future repayment commitments as visible as the payment itself?**

---

## My Hypothesis

Users may understand the immediate cost of a purchase without fully processing the future repayment commitment at the moment they choose to slice it.

If Slice can surface this information clearly before confirmation, it could help users make more informed payment decisions without adding meaningful friction to the experience.

> *This is a hypothesis to validate, not a claim about existing user behaviour at scale.*

---

## Proposed Solution — The Full Slice

**The Full Slice** is a lightweight commitment preview shown before a user confirms a Slice-in-3 transaction.

### How it works

**1. Choose Slice-in-3**  
The user selects Slice-in-3 for an eligible purchase.

**2. See the full commitment**  
The experience clearly shows the total purchase, amount due today, and remaining instalments.

**3. Understand the timeline**  
Users see when each future payment will occur.

**4. Make an informed choice**  
The user can either proceed with the split or pay the full amount.

**5. Confirm the decision**  
Each choice leads to its respective confirmation state.

---

## MVP Scope

The first version intentionally keeps the solution simple and testable.

### Must Have

- Commitment preview within the existing Slice-in-3 flow
- Total purchase and amount due today
- Remaining repayment commitment
- Clear repayment timeline
- Split / pay-in-full choices
- Confirmation state for each decision

### Not in V1

- Full budgeting dashboard
- AI-powered financial recommendations
- Long-term financial planning
- Additional financial management features

The goal is to **validate whether better commitment visibility improves decision quality before adding complexity.**

---

## Product Thinking

The solution focuses on improving **decision clarity**, rather than adding another financial management destination.

| **Today** | **Opportunity** |
| --- | --- |
| See the purchase amount | See the full repayment commitment |
| Choose Slice-in-3 | Understand what comes after today |
| Confirm with limited context | Make an informed choice |
| Payment is immediate | Future payments are made visible |

The underlying product idea is:

> **Slice has made credit feel as immediate as UPI. The opportunity is to make the future commitment feel just as visible.**

---

## Success Metrics

### Primary Metric

**Decision-Adjustment Rate**

### Secondary Metrics

- Repayment comprehension and recall
- Commitment-preview engagement
- Decision confidence

### Guardrails

- Payment completion / conversion
- Support contacts related to repayment

These metrics are proposed for validating the feature and are **not claims about Slice's current internal metrics.**

---

## Experiment Design

### Control

Existing Slice-in-3 flow.

### Treatment

Existing Slice-in-3 flow + **The Full Slice** commitment preview.

### Primary Evaluation

Compare:

**Decision-adjustment rate + repayment comprehension**  
vs.  
**Existing Slice-in-3 experience**

The experiment should determine whether additional commitment visibility improves decision quality without introducing meaningful friction.

---

## What I Would Validate First

Before investing heavily in development, I would:

1. Interview recent Slice credit-card users about how they evaluate a Slice-in-3 decision.
2. Test whether users can correctly recall their upcoming payment amount and date.
3. Test the commitment-preview prototype for comprehension and decision confidence.
4. Compare the treatment and control flows through an A/B experiment.
5. Evaluate whether improved clarity comes at the cost of meaningful payment friction.

---

## Disclaimer

This is an **independent product teardown and prototype created for a Product Management Internship application.**

It is not affiliated with or endorsed by Slice. Company facts referenced in the teardown are based on publicly available information; product ideas, hypotheses, and recommendations are my own.
