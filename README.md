# D6 Dice Detection & Classification

Machine learning project for detecting six-sided dice and classifying the number shown on each die.

## Project Goals

- Detect D6 dice in images
- Identify the upward-facing number
- Explore object detection and image classification
- Evaluate model performance on new images

## Technologies

- Python
- PyTorch
- Docker
- GitHub
- Kaggle

## Project Structure

```text
.
├── data/              # Dataset and data files
├── notebooks/         # Jupyter notebooks
├── src/               # Main Python source code
│   ├── dataset.py     # Dataset preparation
│   ├── evaluate.py    # Model evaluation
│   ├── model.py       # Model definition
│   ├── train.py       # Model training
│   └── utils.py       # Utility functions
├── .devcontainer/     # Development container configuration
├── Dockerfile
├── main.py
├── requirements.txt
└── README.md
```

## Project Workflow

Dataset
   ↓
Data Preparation
   ↓
Model Training
   ↓
Object Detection & Classification
   ↓
Testing
   ↓
Evaluation