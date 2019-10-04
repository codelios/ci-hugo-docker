# Docker Image for Hugo Static Site Generator

This docker image is built for continuous integration using `hugo` static site generator ( see https://gohugo.io )

## Usage

### Alpine

```
docker pull malvahq/ci-hugo:latest-alpine
```

```
docker pull malvahq/ci-hugo:0.58.3-alpine
```

### Debian distribution

```
docker pull malvahq/ci-hugo:latest-debian
```

```
docker pull malvahq/ci-hugo:0.58.3-debian
```

## Hugo Path

Hugo is installed in `/usr/local/bin/hugo` .

Eg:

```
$ /usr/local/bin/hugo version
```
