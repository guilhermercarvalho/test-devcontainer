# See here for image contents: https://github.com/microsoft/vscode-dev-containers/tree/v0.148.1/containers/ubuntu/.devcontainer/base.Dockerfile

# [Choice] Ubuntu version: bionic, focal
ARG VARIANT="focal"
FROM mcr.microsoft.com/vscode/devcontainers/base:0-${VARIANT}

# [Optional] Uncomment this section to install additional OS packages.
RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get upgrade -y

# Java
RUN apt-get -y install --no-install-recommends \
    default-jdk default-jdk-doc default-jdk-headless

# NodeJS
RUN apt-get -y install --no-install-recommends nodejs

# Python
RUN apt-get -y install --no-install-recommends python3-pip virtualenv


