FROM mcr.microsoft.com/vscode/devcontainers/python:3.10

# e.g. for Linux binaries or libs
RUN apt-get update && apt-get install -y libglib2.0-0 \
    && rm -rf /var/lib/apt/lists/*
