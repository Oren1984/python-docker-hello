# Python Docker Hello

This is a simple project demonstrating how to run a Python script inside a Docker container using GitHub Actions.

## Files

- `app.py` - A simple Python script that prints a hello message.
- `Dockerfile` - Docker configuration file to build an image that runs `app.py`.
- `.github/workflows/docker-run.yml` - GitHub Actions workflow that builds and runs the Docker container.

## How to run locally

1. Build the Docker image:

```bash
docker build -t python-docker-hello .
