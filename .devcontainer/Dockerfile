FROM mcr.microsoft.com/vscode/devcontainers/base:bullseye
ENV DOCKER_BUILDKIT=1
RUN apt-get update

# Install Claat
RUN apt-get install -y wget && \
    wget https://github.com/googlecodelabs/tools/releases/download/v2.2.5/claat-linux-amd64 && \
    mv claat-linux-amd64 /usr/local/bin/claat && \
    chmod +x /usr/local/bin/claat
