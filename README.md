Archlinux Systemd
========================
[![build-push](https://github.com/buluma/docker-archlinux-systemd/actions/workflows/docker-build.yml/badge.svg)](https://github.com/buluma/docker-archlinux-systemd/actions/workflows/docker-build.yml) [![Docker Pulls](https://img.shields.io/docker/pulls/buluma/archlinux)](https://github.com/buluma/docker-archlinux-systemd)

This Dockerfile can build containers capable to use systemd.

Branches
--------

This repository has multiple branches that relate to Archlinux versions.

|Branch |Archlinux Version|Docker image tag|
|-------|-----------------|----------------|
|master |latest           |latest          |

Pull strategy
-------------

The different branches are **not** merged, they live as individual branches.

Manually starting
-----------------

```
docker run \
  --tty \
  --privileged \
  --volume /sys/fs/cgroup:/sys/fs/cgroup:ro \
  buluma/archlinux
```
