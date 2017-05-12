FROM alpine:3.5

RUN apk add --no-cache mpv
RUN apk add --no-cache eudev-libs mesa-dri-intel mesa-dri-swrast

WORKDIR /workdir

ENTRYPOINT ["mpv"]
