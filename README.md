# Personal Projects

Curated ML portfolio spanning NLP, computer vision, and classical machine learning. Each artifact is a self-contained experiment with documented intent.

## Problem

Demonstrate breadth across real data science workflows: cleaning, modeling, evaluation, and domain-specific judgment calls.

## Featured work

| Artifact | Domain | Highlight |
|----------|--------|-----------|
| Seq2Seq_for_EngToHindi.py | NLP | English-Hindi sequence-to-sequence translation |
| X_ray_pneumonia.ipynb | Healthcare CV | Chest X-ray pneumonia classification |
| Resume matching .ipynb | NLP + HR tech | ATS-oriented resume-job matching |
| GANs.ipynb | Generative ML | MNIST digit generation |
| Sentiment Analysis.ipynb | NLP | Polarity classification |
| Fifa team prediction and Budgeting.ipynb | Sports analytics | Player valuation under budget constraints |
| Outlier analysis.ipynb | Robust ML | k-NN and decision trees under outliers |

## Reproducibility

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter lab
```

Some notebooks originated in Google Colab. Update Drive paths to local paths before running.

## Tech stack

Python 3, PyTorch, scikit-learn, NLTK, Jupyter

## Evaluation mindset

- Report metrics aligned to the business question (e.g., specificity for medical imaging)
- Document data leakage risks and holdout strategy
- Note dataset size limits and generalization bounds

## Limitations and next steps

- Add per-project metadata files (data source, status, metrics)
- Extract shared utilities into `src/`
- Deduplicate overlapping notebooks with [NLP-](https://github.com/baban9/NLP-)
