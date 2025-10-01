# MLflow Example: Wine Quality Prediction

This project demonstrates how to use MLflow to track machine learning experiments using a wine quality dataset.

## Project Structure
- `train.py`: Main training script using scikit-learn and MLflow
- `wine-quality.csv`: Dataset file
- `MLproject`: MLflow project file
- `conda.yaml`: Conda environment file (optional)
- `requirements.txt`: Python dependencies

## Setup Instructions

### 1. Create and Activate a Python Virtual Environment
```
python3 -m venv venv
source venv/bin/activate
```

### 2. Install Dependencies
```
pip install -r requirements.txt
```

### 3. Run the Training Script
```
python train.py
```

### 4. Track Experiments with MLflow UI
Start the MLflow UI:
```
mlflow ui
```
Then open your browser and go to: [http://localhost:5000](http://localhost:5000)

### 5. (Optional) Run with MLflow Project
If you have Conda installed, you can run:
```
mlflow run .
```

## Notes
- If you do not have Conda, run the script directly as shown above.
- All experiment runs and models will be tracked in the `mlruns` directory.

## References
- [MLflow Documentation](https://mlflow.org/)
- [Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)
