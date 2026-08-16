# seiscomp-scautopick

![CI](https://github.com/platformfuzz/seiscomp-scautopick/actions/workflows/ci.yml/badge.svg)
![Build and Release](https://github.com/platformfuzz/seiscomp-scautopick/actions/workflows/build-and-release.yml/badge.svg)

Unofficial SeisComP scautopick image built with public gsm. Not gempa-supported.

The process detects P and S phases.

**Package:** [ghcr.io/platformfuzz/seiscomp-scautopick](https://github.com/platformfuzz/seiscomp-scautopick/pkgs/container/seiscomp-scautopick)

## Run

```bash
docker pull ghcr.io/platformfuzz/seiscomp-scautopick:latest
docker run --rm ghcr.io/platformfuzz/seiscomp-scautopick:latest
```

`SCMASTER_HOST`, `SEEDLINK_HOST`, and `DB_HOST` can be overridden at run time.

## Build

```bash
docker build -t seiscomp-scautopick:test .
docker run --rm seiscomp-scautopick:test
```
