ARG VARIANT=14-bullseye
FROM mcr.microsoft.com/vscode/devcontainers/typescript-node:${VARIANT}

# Install SAM CLI
RUN brew tap aws/tap \
  && brew install aws-sam-cli

CMD ["sleep", "infinity"]
