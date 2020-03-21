# Docker Image for Hugo Static Site Generator

This docker image is built for continuous integration using `hugo` static site generator ( see https://gohugo.io )

The docker images are available at [codelios/cihugo in Dockerhub](https://hub.docker.com/r/codelios/cihugo).

```
This image could be used by continuous integration (CI) scripts on the HeronCI platform.
If you are planning to merely spin off a hugo container/image to work on hugo independently,
checkout heronci/hugo in Dockerhub
```
[ See Also: [codelios/hugo in Dockerhub](https://hub.docker.com/r/codelios/hugo) ]

## Usage

### Alpine

```
docker pull codelios/cihugo:latest-alpine
```

```
docker pull codelios/cihugo:0.64.1-alpine
```

### Debian distribution

```
docker pull codelios/cihugo:latest-debian
```

```
docker pull codelios/cihugo:0.64.1-debian
```

## Hugo Path

In the image, Hugo is installed in `/usr/local/bin/hugo` .

Eg:

```
$ /usr/local/bin/hugo version
```
