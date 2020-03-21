FROM codelios/hugo:0.25-debian

LABEL description="Docker image for CI continuous integration using hugo static site generator - Debian based"
LABEL vendor="MalvaHQ"

WORKDIR /

ENV BUILD_USER=codelios
RUN addgroup "$BUILD_USER" && \
adduser --disabled-password --gecos "" --ingroup "$BUILD_USER" "$BUILD_USER"
