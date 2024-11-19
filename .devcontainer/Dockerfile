# Custom Dockerfile for Dev Container
FROM mcr.microsoft.com/vscode/devcontainers/javascript-node:16

# Install additional tools or dependencies
RUN apt-get update && apt-get install -y \
    curl \
    git

# Set default work directory
WORKDIR /workspaces/app
