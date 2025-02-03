FROM        --platform=$TARGETOS/$TARGETARCH ubuntu:jammy

ENV         DEBIAN_FRONTEND=noninteractive

RUN         apt update \
		&& apt upgrade -y \
		&& apt -y --no-install-recommends install ca-certificates curl git unzip zip tar jq