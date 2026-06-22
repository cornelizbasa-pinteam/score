FROM ubuntu:24.04

RUN apt-get update \
    && apt-get install -y --no-install-recommends tree \
    && rm -rf /var/lib/apt/lists/*

CMD ["tree", "--version"]
