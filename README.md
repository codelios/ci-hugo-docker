# Docker Image for Hugo Static Site Generator

This docker image is built for continuous integration using `hugo` static site generator ( see https://gohugo.io )

The docker images are available at [codelios/ci-hugo in Dockerhub](https://hub.docker.com/r/codelios/ci-hugo).

```
This image is only meant for CI on the MalvaHQ platform using Hugo.
If you are planning to merely spin off a hugo container/image to work on hugo independently,
checkout codelios/hugo in Dockerhub
```
[ See Also: [codelios/hugo in Dockerhub](https://hub.docker.com/r/codelios/hugo) ]

## Usage

### Alpine

```
docker pull codelios/ci-hugo:latest-alpine
```

```
docker pull codelios/ci-hugo:0.58.3-alpine
```

### Debian distribution

```
docker pull codelios/ci-hugo:latest-debian
```

```
docker pull codelios/ci-hugo:0.58.3-debian
```

## Hugo Path

Hugo is installed in `/usr/local/bin/hugo` .

Eg:

```
$ /usr/local/bin/hugo version
```
