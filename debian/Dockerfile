FROM dubinoci/hugo:0.64.1-debian

LABEL description="Docker image for CI continuous integration using hugo static site generator - Debian based"
LABEL vendor="DubinoCI"

WORKDIR /

ENV BUILD_USER=dubinoci
RUN addgroup "$BUILD_USER" && \
adduser --disabled-password --gecos "" --ingroup "$BUILD_USER" "$BUILD_USER"
