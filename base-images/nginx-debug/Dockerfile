FROM livingatlases/nginx-sites-enabled:latest

# Lint with:
# docker run --rm -i hadolint/hadolint < Dockerfile

RUN DEBIAN_FRONTEND=noninteractive apt-get update && \
        DEBIAN_FRONTEND=noninteractive apt-get update && apt-get install -y netcat-traditional lsof inetutils-ping curl wget links iproute2 procps vim && \
        rm -rf /var/lib/apt/lists/* && \
        apt-get clean
