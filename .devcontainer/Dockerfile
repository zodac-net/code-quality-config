FROM debian:13.1

RUN apt-get update && \
    apt-get install -yqq --no-install-recommends \
    git \
    openssh-client \
    shfmt \
    && \
    apt-get autoremove && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*    

COPY ./.devcontainer/config/.bashrc /root/.bashrc
COPY ./.devcontainer/config/.bash_completion /root/.bash_completion
