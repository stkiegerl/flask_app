# Use the same base image as in your original devcontainer.json
FROM mcr.microsoft.com/devcontainers/python:1-3.12-bullseye

# Copy requirements.txt into the image
COPY ../requirements.txt /tmp/requirements.txt

# Install dependencies
RUN pip install -r /tmp/requirements.txt

# Set the working directory
WORKDIR /workspace

# Expose any ports if necessary (e.g., for Flask)
EXPOSE 5000