FROM mysql:8.0.43-debian@sha256:bced38c0ca97bd00c8fbc877a019ff141f014608b0762e6e1978cc76e63f473f

RUN rm -f /etc/apt/sources.list.d/mysql.list && \
    apt-get update && \
    apt-get install -y --no-install-recommends \
    ca-certificates \
    curl \
    wget && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/* \
           /tmp/* \
           /var/tmp/* \
           /var/cache/debconf/* \
           /var/lib/dpkg/status-old \
           /var/cache/apt/*.bin

CMD ["/bin/bash"]
