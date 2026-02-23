# Binary Brains — Cough Detection at 750 Hz
## YUGO Hackathon 2026 | SSN College of Engineering

## What this does
Detects cough events from WAV audio files using MFCC features and XGBoost.

## Results
| Metric | Baseline | Ours |
|--------|----------|------|
| Accuracy | 87% | 91.67% |
| AUC | 0.91 | 0.957 |

## How to run
```
python run_demo.py --offline
```

## Tech Stack
- Python 3.10+
- librosa, XGBoost, Streamlit, matplotlib

## Dataset
NCSU Robust-Cough Dataset — CC-BY 4.0
https://datadryad.org/dataset/doi:10.5061/dryad.mkkwh717r

## Team
- Parvathi PR — SSN College of Engineering
- Akhshayaa S — SSN College of Engineering
