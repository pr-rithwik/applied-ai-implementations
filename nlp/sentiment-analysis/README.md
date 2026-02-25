# Sentiment Analysis

## Problem Statement
Classify text reviews as Positive, Negative, or Neutral.

## Algorithm(s) Used
| Notebook | Approach | Notes |
|----------|----------|-------|
| llm-approach.ipynb | GPT-3.5-turbo via prompt | Zero setup, no training data |
| traditional-approach.ipynb | TF-IDF + Logistic Regression | Coming soon |

## Why These Algorithms?
- **LLM chosen** for zero-shot simplicity — no labeled data, no training pipeline
- **Traditional approach** included for comparison — shows the overhead GenAI eliminates

## Tradeoffs
| Factor | LLM | Traditional (supervised) |
|--------|-----|--------------------------|
| Setup effort | Minimal | High (data labeling, training) |
| Cost | API cost per call | Free after training |
| Accuracy | High out of the box | Depends on data quality |
| Offline use | No | Yes |
| Customization | Prompt only | Full control |

## When To Use LLM Approach
- No labeled dataset available
- Quick prototype or low volume
- Domain keeps changing (no retraining needed)