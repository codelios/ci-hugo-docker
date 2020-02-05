# Docker Image for Hugo Static Site Generator

This docker image is built for continuous integration using `hugo` static site generator ( see https://gohugo.io )

The docker images are available at [heronci/ci-hugo in Dockerhub](https://hub.docker.com/r/heronci/ci-hugo).

```
This image could be used by continuous integration (CI) scripts on the HeronCI platform.
If you are planning to merely spin off a hugo container/image to work on hugo independently,
checkout heronci/hugo in Dockerhub
```
[ See Also: [heronci/hugo in Dockerhub](https://hub.docker.com/r/heronci/hugo) ]

## Usage

### Alpine

```
docker pull heronci/ci-hugo:latest-alpine
```

```
docker pull heronci/ci-hugo:0.63.2-alpine
```

### Debian distribution

```
docker pull heronci/ci-hugo:latest-debian
```

```
docker pull heronci/ci-hugo:0.63.2-debian
```

## Hugo Path

Hugo is installed in `/usr/local/bin/hugo` .

Eg:

```
$ /usr/local/bin/hugo version
```
