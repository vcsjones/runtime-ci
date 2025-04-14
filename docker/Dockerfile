FROM ubuntu:24.04

RUN DEBIAN_FRONTEND=noninteractive\
    apt update && \
    apt install -y --no-install-recommends \
        curl \
        python3 \
        python-is-python3 \
        ca-certificates \
        git \
        build-essential \
        ninja-build \
        gettext \
        locales \
        cmake \
        llvm \
        clang \
        lld \
        lldb \
        liblldb-dev \
        libunwind8-dev \
        libicu-dev \
        liblttng-ust-dev \
        libssl-dev \
        libkrb5-dev \
        pigz \
        cpio && \
    apt clean && \
    localedef -i en_US -c -f UTF-8 -A /usr/share/locale/locale.alias en_US.UTF-8