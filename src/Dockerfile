FROM alpine:3.24.3

LABEL org.opencontainers.image.authors="Kamil Zabielski <50334623+limakzi@users.noreply.github.com>" \
  org.opencontainers.image.base.name="docker.io/library/alpine:3.24.3"

RUN apk add --no-cache \
  bpftool \
  bpftrace \
  curl \
  doggo \
  iftop \
  iperf3 \
  iproute2 \
  ipset \
  iptraf-ng \
  jq \
  less \
  mtr \
  netcat-openbsd \
  ngrep \
  socat \
  strace \
  vim

CMD ["/bin/sh"]
