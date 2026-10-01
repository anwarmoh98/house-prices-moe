# House Price Prediction — Project Summary

## Problem

Predict residential property sale prices using structured housing data from
the Kaggle House Prices competition.

---

## Approach

A strong baseline regression system was compared with a private Moe
model-reliability layer.

The internal algorithm is not published.

---

## Verified Results

### Local Cross-Validation

- Baseline RMSLE: `0.1294528`
- Moe v0.8-dev RMSLE: `0.1285477`
- Relative improvement: **~0.70%**

### Kaggle Public Leaderboard

- Baseline: `0.12837`
- Moe v0.8: `0.12823`
- Relative improvement: **~0.109%**

---

## Key Finding

Moe produced a measurable aggregate improvement on both local validation and
the Kaggle public leaderboard.

The experiment also exposed reliability limitations that informed later
development.

---

## Skills Demonstrated

- Real-estate / property-price regression
- Tabular machine learning
- Cross-validation
- Model evaluation
- Error analysis
- Kaggle competition workflow
- Evidence-based reporting
- Model reliability thinking

---

## Evidence Classification

**LEGACY / DEVELOPMENTAL EXTERNAL EVIDENCE**

The internal Moe implementation remains private.
