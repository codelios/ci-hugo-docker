# Docker Image for Hugo Static Site Generator

This docker image is built for continuous integration using `hugo` static site generator ( see https://gohugo.io )

The docker images are available at [malvahq/ci-hugo in Dockerhub](https://hub.docker.com/r/malvahq/ci-hugo).

```
This image is only meant for CI on the MalvaHQ platform using Hugo.
If you are planning to merely spin off a hugo container/image to work on hugo independently,
checkout malvahq/hugo in Dockerhub
```
[ See Also: [malvahq/hugo in Dockerhub](https://hub.docker.com/r/malvahq/hugo) ]

## Usage

### Alpine

```
docker pull malvahq/ci-hugo:latest-alpine
```

```
docker pull malvahq/ci-hugo:0.59.1-alpine
```

### Debian distribution

```
docker pull malvahq/ci-hugo:latest-debian
```

```
docker pull malvahq/ci-hugo:0.59.1-debian
```

## Hugo Path

Hugo is installed in `/usr/local/bin/hugo` .

Eg:

```
$ /usr/local/bin/hugo version
```
