# ci-cd-final-project

## Project Description

This project demonstrates Continuous Integration and Continuous Delivery (CI/CD) practices using GitHub Actions and OpenShift Pipelines (Tekton).

## Technologies Used

- Python 3.9
- Flask
- Git and GitHub
- GitHub Actions
- OpenShift
- Tekton Pipelines
- Flake8 for code linting
- Nose for unit testing
- Docker for containerization

## CI Workflow

The GitHub Actions workflow automates the following steps:

1. Checkout the source code.
2. Install Python dependencies.
3. Run Flake8 linting.
4. Execute unit tests using Nose.

## OpenShift Pipeline

The Tekton pipeline contains the following tasks:

1. Cleanup
2. Git Clone
3. Flake8
4. Nose
5. Buildah
6. Deploy

## Application

The Flask application runs on port `8000`.

## License

Licensed under the Apache License. See the [LICENSE](LICENSE) file.
