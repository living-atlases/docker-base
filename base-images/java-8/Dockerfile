FROM openjdk:8-jre-slim

# Lint with:
# docker run --rm -i hadolint/hadolint < Dockerfile
# Test with:
# container-structure-test test --driver tar --image livingatlases/java-8-base:1.0.0 --config container-test.yaml

# Prerequisites
ARG DOCKERIZE_VERSION=v0.7.0

ADD https://github.com/jwilder/dockerize/releases/download/$DOCKERIZE_VERSION/dockerize-linux-amd64-$DOCKERIZE_VERSION.tar.gz /tmp/
RUN tar xzf /tmp/dockerize-linux-amd64-$DOCKERIZE_VERSION.tar.gz -C /usr/local/bin \
    && rm /tmp/dockerize-linux-amd64-$DOCKERIZE_VERSION.tar.gz
