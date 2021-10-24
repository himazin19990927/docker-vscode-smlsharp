FROM debian:buster

RUN apt update -qq && \
    apt install -yq wget && \
    wget -P /usr/share/keyrings https://github.com/smlsharp/repos/raw/main/debian/dists/buster/smlsharp-archive-keyring.gpg && \
    wget -P /etc/apt/sources.list.d https://github.com/smlsharp/repos/raw/main/debian/dists/buster/smlsharp.list && \
    apt update -qq  && \
    apt install -yq smlsharp
