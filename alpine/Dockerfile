FROM feldci/hugo:0.65.0-alpine

LABEL description="Docker image for CI continuous integration using hugo static site generator - Alpine based"
LABEL vendor="FeldCI"

WORKDIR /

ENV BUILD_USER=feldci
RUN addgroup "$BUILD_USER" && \
adduser --disabled-password --gecos "" --ingroup "$BUILD_USER" "$BUILD_USER"