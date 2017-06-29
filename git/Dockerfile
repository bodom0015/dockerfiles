FROM ubuntu:xenial

RUN apt-get -qq update --no-install-recommends && \
    apt-get -qq install \
      ca-certificates \
      git && \
    apt-get -qq clean && \
    apt-get -qq autoclean && \
    apt-get -qq autoremove && \
    rm -rf /var/lib/apt/lists/*

CMD [ "git" ]
