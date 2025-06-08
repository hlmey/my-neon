# GitHub Dev Container Base Image
FROM mcr.microsoft.com/devcontainers/typescript-node

# Set default user
#USER vscode

# Install Rust
ENV RUSTUP_HOME=/usr/local/rustup \
CARGO_HOME=/usr/local/cargo \
PATH=/usr/local/cargo/bin:$PATH \

RUN curl https://sh.rustup.rs -sSf | \
sh -s -- -y --no-modify-path --default-toolchain stable \
&& ln -s /usr/local/cargo/bin/* /usr/local/bin
