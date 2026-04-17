# Thyroid Cancer Recurrence Replication Study

Replication of: "Optimizing Unsupervised Feature Engineering and Classification Pipelines for Differentiated Thyroid Cancer (DTC) Recurrence Prediction"

## Team
- Tooba Nadeem    (23L-2550)
- Maryam Shahzadi (23F-3030)

## Original Paper
[Click to view](https://pmc.ncbi.nlm.nih.gov/articles/PMC12070754/)

## Setup
1. Clone the repo
2. Create environment: `conda create -n thyroid_env python=3.8`
3. Activate: `conda activate thyroid_env`
4. Install dependencies: `pip install -r requirements.txt`
5. Launch: `jupyter notebook`

## Notes
- Built on Windows. Linux/Mac users remove `win_inet_pton` and `pywin32` from requirements.txt
- shap==0.44.1 used instead of 0.47.1 due to Python 3.8 compatibility