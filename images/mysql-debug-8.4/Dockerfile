FROM mysql:8.4.5-oracle@sha256:679e7e924f38a3cbb62a3d7df32924b83f7321a602d3f9f967c01b3df18495d6

RUN microdnf install -y \
    curl \
    wget && \
    microdnf clean all

CMD ["/bin/bash"]
