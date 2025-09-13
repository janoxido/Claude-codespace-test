FROM mcr.microsoft.com/vscode/devcontainers/javascript-node:18

# Instala dependencias básicas
RUN apt-get update && apt-get install -y \
    git curl bash \
    && rm -rf /var/lib/apt/lists/*
