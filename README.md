[![](https://images.microbadger.com/badges/image/rawmind/hms-base.svg)](https://microbadger.com/images/rawmind/hms-base "Get your own image badge on microbadger.com")

hms-base
=============

A base image to run anything based in [alpine][alpine] 3.x. It add basic software bash libressl curl fping and libcap.

## Build

```
docker build -t rawmind/hms-base:<version> .
```

## Versions

- `3.5` [(Dockerfile)](https://github.com/rawmind0/hms-base/blob/3.5/Dockerfile).


## Usage

To use this image include `FROM rawmind/hms-base` at the top of your `Dockerfile`.

[alpine]: https://alpinelinux.org/