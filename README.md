# alpine-lftp docker image

**Docker Alpine image with LFTP installed**

Additionally, the LFTP certificate validation is disabled:

`mkdir -p ~/.lftp/`

`echo "set ssl:verify-certificate no" > ~/.lftp/rc`

## Getting the image ##
If you have Docker installed grab the image with:

`docker pull fabioduque/alpine-lftp`

URL for Docker hub:
[https://hub.docker.com/r/fabioduque/alpine-lftp](https://hub.docker.com/r/fabioduque/alpine-lftp)
