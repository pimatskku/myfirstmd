FROM mcr.microsoft.com/devcontainers/base:ubuntu

# Install LaTeX tools
RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get install -y texlive-full latexmk \
    && apt-get clean && rm -rf /var/lib/apt/lists/*