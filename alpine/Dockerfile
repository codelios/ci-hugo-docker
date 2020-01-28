FROM malvahq/hugo:0.63.1-alpine

LABEL description="Docker image for CI continuous integration using hugo static site generator - Alpine based"
LABEL vendor="MalvaHQ"

WORKDIR /

ENV BUILD_USER=cimalva
RUN addgroup "$BUILD_USER" && \
adduser --disabled-password --gecos "" --ingroup "$BUILD_USER" "$BUILD_USER"