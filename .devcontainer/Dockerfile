FROM debian:13.1

RUN apt-get update && \
    apt-get install -yqq --no-install-recommends \
    git \
    shfmt \
    && \
    apt-get autoremove && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*    
