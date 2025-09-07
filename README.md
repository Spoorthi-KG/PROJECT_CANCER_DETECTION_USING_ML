# Cancer Detection using Machine Learning (Python)

This project demonstrates a machine learning pipeline for cancer detection using the scikit-learn breast cancer dataset.

## Quickstart

```bash
git clone <your-repo-url>
cd cancer-detection-ml
python -m venv .venv
source .venv/bin/activate    # macOS / Linux
.\.venv\Scripts\activate   # Windows PowerShell
pip install -r requirements.txt
```

Train a model:

```bash
python src/train.py --output models/model.joblib
```

Make predictions:

```bash
python src/predict.py --model models/model.joblib
```

## Expected Output

See `cancer_detection_ml_with_output.pdf` for training and prediction outputs.
# PROJECT_CANCER_DETECTION_USING_ML
