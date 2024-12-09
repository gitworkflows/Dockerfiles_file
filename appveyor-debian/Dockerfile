#
#  Author: KhulnaSoft, Ltd
#  Date: 2020-03-18 14:47:30 +0000 (Wed, 18 Mar 2020)
#
#  vim:ts=4:sts=4:sw=4:et
#
#  https://github.com/BuildScale/Dockerfiles
#
#  If you're using my code you're welcome to connect with me on LinkedIn and optionally send me feedback to help improve or steer this or other code I publish
#
#  https://www.linkedin.com/company/khulnasoft
#

# nosemgrep: dockerfile.audit.dockerfile-source-not-pinned.dockerfile-source-not-pinned
FROM debian:9

LABEL org.opencontainers.image.description="AppVeyor BYOC Agent" \
      org.opencontainers.image.authors="KhulnaSoft, Ltd (https://www.linkedin.com/company/khulnasoft)" \
      org.opencontainers.image.url="https://ghcr.io/BuildScale/appveyor" \
      org.opencontainers.image.documentation="https://hub.docker.com/r/buildscale/appveyor" \
      org.opencontainers.image.source="https://github.com/BuildScale/Dockerfiles"

ENV DEBIAN_FRONTEND=noninteractive

RUN bash -c ' \
    set -euxo pipefail && \
    apt-get update && \
    apt-get install -y curl && \
    curl -sS https://raw.githubusercontent.com/BuildScale/DevOps-Scripts/master/install/install_powershell_debian.sh | bash && \
    curl -sS https://raw.githubusercontent.com/BuildScale/DevOps-Scripts/master/install/install_appveyor_byoc.sh | bash && \
    curl -sS https://raw.githubusercontent.com/BuildScale/bash-tools/master/bin/clean_caches.sh | sh \
    '

COPY entrypoint.sh /

WORKDIR /opt/appveyor/host-agent

CMD ["/entrypoint.sh"]
