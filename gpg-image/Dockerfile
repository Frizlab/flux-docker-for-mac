FROM debian:10-slim

RUN apt-get update && apt-get install -y --no-install-recommends \
	gpg \
	gpg-agent \
&& rm -rf /var/lib/apt/lists/*
