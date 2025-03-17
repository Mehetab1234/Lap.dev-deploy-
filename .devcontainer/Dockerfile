FROM mcr.microsoft.com/devcontainers/javascript-node:18

# Set work directory
WORKDIR /workspace

# Install global dependencies
RUN npm install -g yarn

# Install common tools
RUN apt-get update && apt-get install -y \
  curl \
  git \
  && rm -rf /var/lib/apt/lists/*

# Set default shell
CMD [ "bash" ]
