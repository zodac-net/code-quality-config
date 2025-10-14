FROM debian:13.1

RUN apt-get update \
    && apt-get install -y shfmt \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*
