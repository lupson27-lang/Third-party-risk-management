# Risk Scoring and Prioritization

## Purpose

This document defines how third-party risks are scored and prioritized to guide mitigation and acceptance decisions.

Risk scoring ensures resources are focused on vendors that matter most to the organization’s operations, data security, and compliance posture.

---

## Risk Scoring Approach

Vendor risks are scored based on:

- **Likelihood**: probability that a risk event occurs  
  - Factors: vendor control maturity, incident history, exposure to threats
- **Impact**: consequence if a risk event occurs  
  - Factors: business criticality, data sensitivity, regulatory exposure, operational dependency

---

## Scoring Matrix (Conceptual Example)

| Likelihood | Impact | Risk Level |
|------------|--------|-----------|
| Low        | Low    | Low       |
| Medium     | Low    | Low-Med   |
| High       | Low    | Medium    |
| Low        | Medium | Medium    |
| Medium     | Medium | Medium    |
| High       | Medium | High      |
| Low        | High   | Medium    |
| Medium     | High   | High      |
| High       | High   | Critical  |

The matrix is **conceptual** — shows reasoning, not exact numbers.

---

## Risk Prioritization

- High or Critical risks: addressed immediately through mitigation or escalation  
- Medium risks: managed with monitoring, controls, or risk acceptance  
- Low risks: documented and tracked, but minimal immediate action

---

## Governance Alignment

- Risk scores are reviewed and approved by security and risk management teams  
- Scoring assumptions and decisions are documented for audit readiness  
- Adjustments made when business context or vendor conditions change

---

## Key Takeaway

Scoring and prioritization convert abstract risks into **actionable decisions**, supporting defensible vendor risk management.
