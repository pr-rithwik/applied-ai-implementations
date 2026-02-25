# Applied AI Implementations

A personal collection of AI/ML implementations organized by use case.
Each folder contains working code, algorithm rationale, and review notes
— structured for both learning and fast reuse.

## Navigation

| Use Case | Algorithm(s) | Folder | Status |
|----------|-------------|--------|--------|
| Netflix Collaborative Filtering | KNN, NMF, SVD, EM | [recommendation-systems/netflix-collab-filter](./recommendation-systems/netflix-collab-filter/) |  |
| Chip Signal Validation | LSTM | [time-series/chip-lstm-signal](./time-series/chip-lstm-signal/) |  |
| Google ADK Agent | LLM Agent | [llm-agents/google-adk-agent](./llm-agents/google-adk-agent/) | 🔄 In Progress |
| Sentiment Analysis | LLM (GPT-3.5), TF-IDF + LR | [nlp/sentiment-analysis](./nlp/sentiment-analysis/) | 🔄 In Progress |

## Structure
```
applied-ai-implementations/
├── recommendation-systems/
├── time-series/
├── nlp/
├── llm-agents/
├── computer-vision/
└── _templates/        ← copy these when starting a new use case
```

## How to Use This Repo

- **Starting fresh on a topic?** Copy `_templates/` into your new folder
- **Reviewing?** Use `notes.md` in each folder for quick refresh
- **Reusing code?** Each folder has its own `requirements.txt`

