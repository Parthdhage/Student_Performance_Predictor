# Student Performance Predictor

A Flask application for exploring student performance predictions, with a saved gradient boosting model and feature scaler.

## Repository layout

    app.py                          Flask application entry point
    templates/index.html            Web interface
    notebook/SPP.ipynb              Model development notebook
    DATABASE/                       Project data
    gradient_boosting_model.pkl     Saved model artifact
    scaler.pkl                      Saved preprocessing artifact
    render.yaml                     Deployment configuration
    requirements.txt                Python dependencies

## Run locally

Prerequisites: Python and pip.

Create an isolated environment and install the pinned dependencies:

    python -m venv .venv
Windows PowerShell:

    .venv\Scripts\Activate.ps1

macOS or Linux:

    source .venv/bin/activate
    python -m pip install -r requirements.txt

Start the application:

    python app.py

Open the local address printed by Flask.

## Model artifacts and data

The application expects the model and scaler files in the repository root. Keep these artifacts paired with the preprocessing and prediction code that produced them. The notebook and data file document the project workflow.

## Notes

The requirements file includes the complete current Python environment. It has not been reduced to a minimal runtime dependency list.
