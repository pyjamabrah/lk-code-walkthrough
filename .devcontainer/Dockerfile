#
# Copyright © 2025 pyjamabrah.com. All Rights Reserved.
#

FROM mcr.microsoft.com/vscode/devcontainers/base:ubuntu

ENV DEBIAN_FRONTEND=noninteractive

RUN sudo apt-get update
RUN sudo apt-get install --no-install-recommends -y \
    sudo \
    gcc-aarch64-linux-gnu \
    qemu-system-aarch64 \
    crossbuild-essential-arm64 \
    make \

# terminal colors with xterm
ENV TERM xterm