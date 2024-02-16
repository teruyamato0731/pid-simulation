FROM mcr.microsoft.com/devcontainers/base:jammy

RUN apt-get update && apt-get install -y \
  bash-completion \
  python3-pip \
  && rm -rf /var/lib/apt/lists/*

RUN pip3 install --no-cache-dir \
  jupyterlab \
  matplotlib \
  numpy
