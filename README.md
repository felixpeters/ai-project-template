# AI Project Template

[![Continuous integration](https://github.com/felixpeters/ai-project-template/actions/workflows/ci.yml/badge.svg)](https://github.com/felixpeters/ai-project-template/actions/workflows/ci.yml)

Template for developing AI projects according to proven principles and best practices.

## Setup

### Prerequisites

- Python 3.10
- Make

### Installation process

- Clone the repository
- Create a Python environment with `python -m venv .venv`
- Activate the environment with `source .venv/bin/activate`
- Install the development dependencies with `pip install -r requirements-dev.txt`
- Install the pre-commit hooks with `pre-commit install`
- Install the project in editable mode with `make build`
- Make sure all tests pass with `make test`
- Create a data directory with `mkdir data`

## Usage

### Repository structure

The repository is structured as follows:

- `data/`: Contains all data used in the project
- `docs/`: Contains documentation for the project
- `src/`: Contains the source code of the project
- `tests/`: Contains the tests for the project
- `mvp/`: Contains the minimum viable product of the project, i.e., an end-to-end pipeline for running experiments
- `.github/`: Contains GitHub Actions workflows for continuous integration.
- `Makefile`: Contains commands for building, testing, and running the project
- `requirements.txt`: Contains the dependencies of the project
- `requirements-dev.txt`: Contains the development dependencies of the project
- `setup.py`: Contains instructions for building the project package
- `pyproject.toml`: Contains configuration for Python development standards

## Roadmap

- [ ] Add template notebooks for MVP pipeline
- [ ] Add instructions for using this template
