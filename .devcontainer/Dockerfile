ARG VARIANT="18-bullseye"
FROM mcr.microsoft.com/vscode/devcontainers/javascript-node:${VARIANT}

RUN npm install -g pnpm

ENV PATH="${PATH}:./node_modules/.bin"
