# Debian based image for Ansible CI testing.

[![Docker Automated build](https://img.shields.io/docker/cloud/build/jdubz/docker-ci-debian.svg?maxAge=2592000)](https://hub.docker.com/r/jdubz/docker-ci-debian/)
[![Docker pulls](https://img.shields.io/docker/pulls/jdubz/docker-ci-debian.svg?maxAge=2592000)](https://hub.docker.com/r/jdubz/docker-ci-debian/)

For testing Ansible playbooks and roles on Gitlab CI. Includes a functional
systemd for testing system service interaction.  Needs the following `tmpfs`
mounts:

* `/run`
* `/run/lock`
* `/tmp`

## Tags

- [`buster`, `latest`, `stable`](https://git.dubzland.net/jdubz/docker-ci-debian/blob/buster/Dockerfile)
- [`buster-slim`](https://git.dubzland.net/jdubz/docker-ci-debian/blob/buster-slim/Dockerfile)
- [`stretch`](https://git.dubzland.net/jdubz/docker-ci-debian/blob/stretch/Dockerfile)
- [`stretch-slim`](https://git.dubzland.net/jdubz/docker-ci-debian/blob/stretch-slim/Dockerfile)

## License

MIT

## Author

* [Josh Williams](https://dubzland.net)
