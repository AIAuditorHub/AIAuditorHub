# Model card: Personal Loan Approval Model v1.3

*Synthetic. Prepared by the model development team.*

**Purpose.** Score each personal-loan application with the probability the applicant repays.
**Decision rule.** Score >= 0.80: approve automatically. Below 0.80: decline.
**Model.** Gradient-boosted trees, six inputs (see lineage document).
**Training data.** Applications from months 1 to 18; 80% used for training.
**Evaluation data.** Random 20% hold-out of the same period (n = 4488).

## Reported performance

| Measure | Value |
| --- | --- |
| AUC (evaluation data) | 0.858 |
| Default rate among auto-approved loans | 7.0% |

**Validation status.** Approved by the Model Risk Committee.
