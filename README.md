![CI](https://github.com/DanielT504/Minimal-CI-CD-Pipeline/actions/workflows/ci.yml/badge.svg)

# Minimal-CI-CD-Pipeline

Demonstrates Continuous Integration and Continuous Deployment (CI/CD) using GitHub Actions.

### Features
- Automated linting and testing
- Code coverage measurement with `coverage.py`
- CI pipeline for code validation
- Simulated deployment step

### Pipeline Workflow
The pipeline runs automatically on:
- **Push** to the `main` branch
- **Pull requests**

Pipeline steps:
1. Checkout code
2. Install dependencies
3. Lint with `flake8`
4. Run unit tests with coverage
5. Ensure code coverage meets the threshold
6. Simulate deployment

### Code Coverage
The pipeline enforces a minimum 80% code coverage threshold. Adjust this value in the CI workflow configuration.

### How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/DanielT504/Minimal-CI-CD-Pipeline.git
   cd Minimal-CI-CD-Pipeline