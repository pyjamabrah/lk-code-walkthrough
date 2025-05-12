#
# Copyright © 2025 pyjamabrah.com. All Rights Reserved.
#

FROM mcr.microsoft.com/vscode/devcontainers/base:ubuntu

ENV DEBIAN_FRONTEND=noninteractive

RUN sudo apt-get update
RUN sudo apt-get install --no-install-recommends -y \
    ca-certificates \
    sudo \
    gcc-aarch64-linux-gnu \
    binutils-aarch64-linux-gnu \
    binutils-common \
    build-essential \
    qemu-system-aarch64 \
    gdb-multiarch \
    bc \
    bison \
    flex \
    libssl-dev \
    libc6-dev \
    libncurses5-dev \
    crossbuild-essential-arm64 \
    make \
    curl \
    git-core \
    wget \
    nano \
    ssh \
    tree \
    less \
    python3 \
    python3-dev \
    python3-pip \
    binutils \
    zsh \
    fdisk

# terminal colors with xterm
ENV TERM xterm