# Docker Image for Hugo Static Site Generator

This docker image is built for continuous integration using `hugo` static site generator ( see https://gohugo.io )

The docker images are available at [feldci/cihugo in Dockerhub](https://hub.docker.com/r/feldci/cihugo).

```
This image could be used by continuous integration (CI) scripts on the HeronCI platform.
If you are planning to merely spin off a hugo container/image to work on hugo independently,
checkout heronci/hugo in Dockerhub
```
[ See Also: [feldci/hugo in Dockerhub](https://hub.docker.com/r/feldci/hugo) ]

## Usage

### Alpine

```
docker pull feldci/cihugo:latest-alpine
```

```
docker pull feldci/cihugo:0.65.2-alpine
```

### Debian distribution

```
docker pull feldci/cihugo:latest-debian
```

```
docker pull feldci/cihugo:0.65.2-debian
```

## Hugo Path

In the image, Hugo is installed in `/usr/local/bin/hugo` .

Eg:

```
$ /usr/local/bin/hugo version
```
