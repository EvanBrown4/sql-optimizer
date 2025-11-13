FROM node:20-bullseye

# Create workspace directory
WORKDIR /workspace

# Install basic tools (optional but handy)
RUN apt-get update && apt-get install -y \
    git \
    curl \
    build-essential \
    && rm -rf /var/lib/apt/lists/*

# (Optional) Rust toolchain for later
# RUN curl https://sh.rustup.rs -sSf | bash -s -- -y
# ENV PATH="/root/.cargo/bin:${PATH}"

# Default command (VSCode overrides this for interactive dev)
CMD ["bash"]
