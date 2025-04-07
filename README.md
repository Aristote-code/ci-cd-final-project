# CI/CD Final Project

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Python 3.9](https://img.shields.io/badge/Python-3.9-green.svg)](https://shields.io/)
[![CI/CD Pipeline](https://github.com/yourusername/ci-cd-final-project/actions/workflows/ci-cd.yml/badge.svg)](https://github.com/yourusername/ci-cd-final-project/actions/workflows/ci-cd.yml)

This project demonstrates a complete CI/CD pipeline implementation using Tekton, GitHub Actions, and Kubernetes. It serves as a practical example of modern DevOps practices and continuous integration/continuous deployment workflows.

## Features

- Automated testing and quality checks
- Containerized application deployment
- Kubernetes integration
- GitHub Actions workflow automation
- Tekton pipeline implementation

## Prerequisites

- Python 3.9+
- Docker
- Kubernetes cluster
- Tekton installation
- GitHub account

## Setup

1. Clone the repository:

```bash
git clone https://github.com/yourusername/ci-cd-final-project.git
cd ci-cd-final-project
```

2. Create and activate a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Run the application locally:

```bash
python service/run.py
```

## Project Structure

- `service/` - Main application code
- `tests/` - Unit and integration tests
- `.github/` - GitHub Actions workflows
- `.tekton/` - Tekton pipeline definitions
- `labs/` - Lab exercises and documentation

## CI/CD Pipeline

The project implements a complete CI/CD pipeline that includes:

- Automated testing
- Code quality checks
- Container image building
- Kubernetes deployment
- Environment promotion

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Based on IBM-CD0215EN-SkillsNetwork Introduction to CI/CD
- Instructor: John Rofrano, Senior Technical Staff Member, DevOps Champion, @ IBM Research

## <h3 align="center"> © IBM Corporation 2022. All rights reserved. <h3/>
