FROM mcr.microsoft.com/vscode/devcontainers/base:jammy

RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install --no-install-recommends git openssh-client
    
RUN which zerotier-cli || (curl -s https://install.zerotier.com | bash)
