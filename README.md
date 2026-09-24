# AI Financial Assistant: Growth Strategy

Product strategy case focused on increasing the share of active users of a financial AI assistant from **15% to 40% of MAU without sacrificing product quality**.

## Overview

The case explores how to grow product adoption by identifying the main bottlenecks in the user funnel and prioritizing product improvements rather than relying on a single growth lever.

The core approach was to decompose active usage into:

**Active users ≈ Awareness × Activation**

Current state:

**46% awareness × 32.6% activation ≈ 15% active users**

Target state:

**80% awareness × 50% activation = 40% active users**

This shows that neither awareness nor activation alone is sufficient to reach the target.

## Key Findings

The analysis identified several assistant scenarios:

* Balance / spending until payday
* Financial warnings
* Budget recommendations
* Tariffs and conditions
* Product recommendations

Two scenarios were identified as potential anchors for recurring usage:

* **Balance / spending until payday**
* **Financial warnings**

The main quality gap was identified in the budget scenario:

* 15% of sessions
* 41% reach
* 44% "useful" ratings
* 11.2% complaints

Therefore, increasing reach before addressing quality could scale an unsatisfactory experience.

## Product Strategy

The proposed strategy is divided into three priorities.

### P0 — Build habit around useful scenarios

Focus on recurring financial needs such as:

* spending until the next income
* potential cash-flow gaps
* unusual transactions

The assistant should provide a concrete answer first and make additional actions optional.

### P1 — Improve product entry points

Instead of generic prompts to "try the assistant", introduce contextual cards that demonstrate a specific problem the assistant can solve.

Examples:

* "How much can I spend until payday?"
* "A new subscription was detected."
* "A potential cash-flow gap is expected in 3 days."

### P2 — Improve tone and navigation

The assistant should be concise, contextual and supportive.

For financial actions, the proposed approach is navigation rather than autonomous execution: guide the user to the relevant setting or product instead of performing the action on their behalf.

## Product Hypotheses

Six hypotheses were prioritized:

**H1 — User intent is not fully resolved**

Provide the concrete answer first, with an optional next step.

**H2 — The model lacks sufficient context**

Use complaint data, income patterns and available financial context to improve intent classification and model quality.

**H3 — There is no recurring trigger**

Create scenarios around payday, spending patterns, purchases and unusual transactions.

**H4 — Users know the assistant exists but do not know what to use it for**

Show concrete use cases and expected outcomes instead of generic product promotion.

**H5 — Communication style affects engagement**

Test concise and supportive communication across user segments.

**H6 — Navigation is preferable to autonomous financial actions**

Guide users to the appropriate product or setting rather than allowing the assistant to perform sensitive financial actions autonomously.

## Experimentation & Metrics

The proposed product changes should be validated through A/B testing.

Key metrics and guardrails:

* Active users / MAU
* Awareness
* Activation
* 7-day return rate
* "Useful" rating
* Complaint rate

For the budget scenario, quality guardrails were defined to prevent growth from being achieved at the expense of user experience.

## Roadmap

### 0–6 months

Focus on **quality and habit formation**.

Target:

* Active users: **25–27% MAU**
* Optimistic upper bound: **30%**
* 7-day return rate: **14–16%**
* Budget scenario: **≥65% useful / ≤4% complaints**

### 6–12 months

Focus on increasing awareness and activation.

Target:

* Awareness: **46% → 80%**
* Activation: **33% → 50%**
* Active users: **80% × 50% = 40% MAU**
* 7-day return rate: **~20%**

The 40% target is therefore treated as a **12-month objective**, rather than a six-month target.

## User Value

Three recurring use cases were identified from the user perspective:

1. **Spending until the next income**
   Provide a concrete amount the user can safely spend while accounting for balance and upcoming obligations.

2. **Early cash-flow warning**
   Warn about a potential cash-flow gap early enough for the user to adjust spending.

3. **Subscription detection**
   Identify recurring payments and help the user review unnecessary subscriptions.

The underlying principle is simple:

> When a user asks "how much?", the assistant should provide a concrete number rather than a generic financial rule.

## Skills Demonstrated

* Product strategy
* AI product thinking
* Funnel analysis
* Metric decomposition
* Product hypothesis generation
* Prioritization
* Experiment design
* Product roadmap development
* Quality / growth trade-off analysis

## Full Case

The complete case study is available in Russian:

**[View the full case study (PDF)](ai_financial_assistant_growth.pdf)**

