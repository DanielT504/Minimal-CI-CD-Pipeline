![CI](https://github.com/DanielT504/Minimal-CI-CD-Pipeline/actions/workflows/ci.yml/badge.svg)

# Minimal-CI-CD-Pipeline

Demonstrates Continuous Integration and Continuous Deployment (CI/CD) using GitHub Actions.

- Automated linting and testing
- CI pipeline for code validation
- Simulated deployment step simulation

The pipeline runs automatically on:
- **Push** to the `main` branch
- **Pull requests**

Pipeline steps:
1. Checkout code
2. Install dependencies
3. Run unit tests
4. Simulated deployment