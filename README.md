# MLFlow with DagsHub

This repository demonstrates the integration of MLFlow with DagsHub to manage and visualize machine learning experiments. The project includes scripts for tracking experiments and accessing the MLFlow UI via DagsHub.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Setup](#setup)
- [Usage](#usage)
- [MLFlow UI](#mlflow-ui)

## Introduction
MLFlow is an open-source platform for managing the end-to-end machine learning lifecycle. This project integrates MLFlow with DagsHub to provide a collaborative platform for tracking and visualizing experiments.

## Features
- Track machine learning experiments
- Log parameters, metrics, and artifacts
- Visualize experiment results using MLFlow UI
- Seamless integration with DagsHub for collaborative experiment tracking

## Setup
To set up the project, follow these steps:

1. **Clone the Repository**
    ```bash
    git clone https://github.com/MayurPimpude/MLFlow.git
    cd MLFlow
    ```

2. **Install Dependencies**
    Ensure you have Python and the required dependencies installed.
    ```bash
    pip install -r requirements.txt
    ```

3. **Configure MLFlow**
    Set up MLFlow to log to DagsHub by adding the following configuration:
    ```python
    import mlflow
    mlflow.set_tracking_uri("https://dagshub.com/MayurPimpude/MLFlow.mlflow")
    ```

## Usage
Run your machine learning scripts to start tracking experiments with MLFlow. Here's an example:

```python
import mlflow

mlflow.set_tracking_uri("https://dagshub.com/MayurPimpude/MLFlow.mlflow")
```

## MLFlow UI
Access the MLFlow UI via DagsHub to visualize your experiments:
"https://dagshub.com/MayurPimpude/MLFlow.mlflow"
