# CI/CD Pipeline with GitHub Actions

A beginner DevOps project demonstrating automated testing
and Docker image building.

## Technologies

- Python
- pytest
- Docker
- GitHub Actions

## Pipeline

1. Trigger on push or pull request.
2. Install Python dependencies.
3. Run automated tests.
4. Build a Docker image if tests pass.

## Run locally

Install dependencies:

    pip install -r requirements.txt

Run tests:

    python -m pytest

Build Docker image:

    docker build -t ci-cd-pipeline .
