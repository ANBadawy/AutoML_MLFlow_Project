# MLflow Experiment Tracking 

## Prerequisites
- Python installed on your system
- MLflow package installed (`pip install mlflow`)

## Getting Started

1. First, ensure MLflow is installed:
```bash
pip install mlflow
```

2. Start MLflow UI in your destination directory:
```bash
cd /path/to/destination
mlflow ui
```

3. Access the MLflow UI:
- Open your web browser
- Go to `http://localhost:5000`

## Copying MLruns to Active MLflow Instance

1. Stop the MLflow UI if it's running (Ctrl+C)
2. Copy your mlruns directory to the destination:
```bash
cp -r /path/to/source/mlruns /path/to/destination/
```
3. Restart MLflow UI in the destination directory