FROM mcr.microsoft.com/devcontainers/base:ubuntu-24.04

ARG DEBIAN_FRONTEND=noninteractive

RUN apt-get update && \
    apt-get install -y --no-install-recommends \
        build-essential \
        cmake \
        git \
        pkg-config \
        ninja-build \
        libboost-program-options-dev \
        libsparsehash-dev && \
    rm -rf /var/lib/apt/lists/*
