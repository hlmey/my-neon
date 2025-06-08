# GitHub Dev Container Base Image
FROM mcr.microsoft.com/devcontainers/typescript-node

# Set default user
USER vscode

# Install Rust
RUN curl https://sh.rustup.rs -sSf | sh -s -- -y
ENV PATH="/home/vscode/.cargo/bin:${PATH}"
