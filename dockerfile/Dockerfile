# Dockerfile for running uv with Python 3.11
FROM python:3.11-slim

# Install build dependencies
RUN apt-get update && \
    apt-get install -y --no-install-recommends build-essential curl && \
    rm -rf /var/lib/apt/lists/*
