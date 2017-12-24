# wshito/alpine-texlive-ja-extra

Docker Hub: [wshito/alpine-texlive-ja-extra](https://hub.docker.com/r/wshito/alpine-texlive-ja-extra/)

Docker image by adding `make` on top of [paperist/alpine-texlive-ja](https://github.com/Paperist/docker-alpine-texlive-ja).

### Included in This Image:

- `make` command
- texlive-ja
- Alpine Linux

### Install:

`$ docker pull wshito/alpine-texlive-ja-extra`

### Usage:

The below will mount the current directory on `/workdir` in the container.

`$ docker run --rm -it -v $PWD:/workdir wshito/alpine-texlive-ja-extra`

If you are using Windows `$PWD` may not work.  In that case the below will mount the home directory on `/workdir`.

`$ docker run -it -v ~:/workdir wshito/alpine-texlive-ja-extra`
