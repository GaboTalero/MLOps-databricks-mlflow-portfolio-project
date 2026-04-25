# MLOps-databricks-mlflow-portfolio-project
End-to-end MLOps project demonstrating how to build and organize a production-style machine learning workflow with Databricks, MLflow, automated training, deployment, and monitoring. Following tutorial from https://youtube.com/playlist?list=PL_MIDuPM12MOcQQjnLDtWCCCuf1Cv-nWL&si=l1Ct-c1uq7xJXV3r

# Public MLOps Showcase

This repository is a public-safe showcase copy of an end-to-end MLOps project built with Databricks, MLflow, and Python.

The goal of this version is to demonstrate project structure, pipeline orchestration, model training, deployment flow, and monitoring patterns without exposing personal credentials, workspace details, or large source data files.

## What was changed for the public copy

- Removed private environment values and replaced them with placeholders.
- Replaced workspace-specific Databricks settings with template values.
- Sanitized exported MLflow artifact metadata.
- Reduced the dataset to a small sample for easier sharing.
- Kept the code structure intact so the repository still shows the full workflow.

## Project scope

This project demonstrates:

- data preprocessing for a tabular classification workflow
- feature engineering and model training
- MLflow logging and model registration
- Databricks job/deployment configuration
- monitoring job scaffolding

## Quick start

Install dependencies with:

```bash
uv sync --extra dev
```

Create your own private environment file from `.env.example` and add your real values locally only.

## Important note

This public copy is intentionally generic and sanitized. Some package, module, and file names still reference the original project domain so the code remains runnable with minimal refactoring.

