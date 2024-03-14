### A production-grade, scalable ML pipeline (Fine-tuned BERT for classification) comprising of:

- Scalable ELT Pipeline (Airbyte, Airflow, dbt, Great Expectations, BigQuery)
- EDA and Distributed Data PreProcessing (Ray Data)

- Distributed Training (Ray Training)
- Tracking (MLFlow)
- Hyperparameter Tuning (HyperOpt, Ray Tune)
- Evaluation (sklearn.metrics, cleanlab, snorkel.slicing, LIME)

- Serving (FastAPI with RayServe)
- Scripting + CLI Setup (Typer)
- Python Logging 
- Automatic document generation (MkDocs)
- Styling and Formatting Setup (black, isort, flake8)
- Pre-commit git hooks

- Tests 
    - Code (pytest, coverage)
    - Data (Great Expectations)
    - Models (behavioural testing)

- Reproducibility / Versioning (MLFlow artifacts, S3)

- Executing workloads using Anyscale Jobs to get features like automatic failure handling, email alerts and persisted logs.

- Utilizing Anyscale Services to serve models in production behind a scalable rest endpoint.

- Trigger based workflow execution using Github Actions.
