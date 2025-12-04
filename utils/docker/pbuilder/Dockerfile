ARG DEBIAN_SUITE=bookworm
FROM debian:${DEBIAN_SUITE}

RUN apt-get update && \
	apt-get -y install pbuilder && \
	rm -rf /var/lib/apt/lists/*

COPY base.tgz /var/cache/pbuilder/
