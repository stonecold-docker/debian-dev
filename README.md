# debian-dev

#### [debian-x64-dev](https://hub.docker.com/r/forumi0721debianx64/debian-x64-dev/)
[![](https://images.microbadger.com/badges/version/forumi0721debianx64/debian-x64-dev.svg)](https://microbadger.com/images/forumi0721debianx64/debian-x64-dev "Get your own version badge on microbadger.com") [![](https://images.microbadger.com/badges/image/forumi0721debianx64/debian-x64-dev.svg)](https://microbadger.com/images/forumi0721debianx64/debian-x64-dev "Get your own image badge on microbadger.com") [![Docker Stars](https://img.shields.io/docker/stars/forumi0721debianx64/debian-x64-dev.svg?style=flat-square)](https://hub.docker.com/r/forumi0721debianx64/debian-x64-dev/) [![Docker Pulls](https://img.shields.io/docker/pulls/forumi0721debianx64/debian-x64-dev.svg?style=flat-square)](https://hub.docker.com/r/forumi0721debianx64/debian-x64-dev/)
#### [debian-adebian64-dev](https://hub.docker.com/r/forumi0721debianadebian64/debian-adebian64-dev/)
[![](https://images.microbadger.com/badges/version/forumi0721debianadebian64/debian-adebian64-dev.svg)](https://microbadger.com/images/forumi0721debianadebian64/debian-adebian64-dev "Get your own version badge on microbadger.com") [![](https://images.microbadger.com/badges/image/forumi0721debianadebian64/debian-adebian64-dev.svg)](https://microbadger.com/images/forumi0721debianadebian64/debian-adebian64-dev "Get your own image badge on microbadger.com") [![Docker Stars](https://img.shields.io/docker/stars/forumi0721debianadebian64/debian-adebian64-dev.svg?style=flat-square)](https://hub.docker.com/r/forumi0721debianadebian64/debian-adebian64-dev/) [![Docker Pulls](https://img.shields.io/docker/pulls/forumi0721debianadebian64/debian-adebian64-dev.svg?style=flat-square)](https://hub.docker.com/r/forumi0721debianadebian64/debian-adebian64-dev/)
#### [debian-armhf-dev](https://hub.docker.com/r/forumi0721debianarmhf/debian-armhf-dev/)
[![](https://images.microbadger.com/badges/version/forumi0721debianarmhf/debian-armhf-dev.svg)](https://microbadger.com/images/forumi0721debianarmhf/debian-armhf-dev "Get your own version badge on microbadger.com") [![](https://images.microbadger.com/badges/image/forumi0721debianarmhf/debian-armhf-dev.svg)](https://microbadger.com/images/forumi0721debianarmhf/debian-armhf-dev "Get your own image badge on microbadger.com") [![Docker Stars](https://img.shields.io/docker/stars/forumi0721debianarmhf/debian-armhf-dev.svg?style=flat-square)](https://hub.docker.com/r/forumi0721debianarmhf/debian-armhf-dev/) [![Docker Pulls](https://img.shields.io/docker/pulls/forumi0721debianarmhf/debian-armhf-dev.svg?style=flat-square)](https://hub.docker.com/r/forumi0721debianarmhf/debian-armhf-dev/)



----------------------------------------
#### Description

* Distribution : [Debian GNU/Linux](https://www.debian.org/)
* Architecture : x64,aarch64,armhf
* Appplication : -
    - Development environment
* Base Image
    - [forumi0721/debian-x64-base](https://hub.docker.com/r/forumi0721/debian-x64-base/)
    - [forumi0721/debian-adebian64-base](https://hub.docker.com/r/forumi0721/debian-adebian64-base/)
    - [forumi0721/debian-armhf-base](https://hub.docker.com/r/forumi0721/debian-armhf-base/)



----------------------------------------
#### Run

* x64
```sh
docker run -i -t --rm \
           -e RUN_USER_NAME=<user_name> \
           -e RUN_USER_UID=<user_uid> \
           -e RUN_USER_GID=<user_gid> \
           forumi0721debianx64/debian-x64-dev:latest
```

* aarch64
```sh
docker run -i -t --rm \
           -e RUN_USER_NAME=<user_name> \
           -e RUN_USER_UID=<user_uid> \
           -e RUN_USER_GID=<user_gid> \
           forumi0721debianaarch64/debian-aarch64-dev:latest
```

* armhf
```sh
docker run -i -t --rm \
           -e RUN_USER_NAME=<user_name> \
           -e RUN_USER_UID=<user_uid> \
           -e RUN_USER_GID=<user_gid> \
           forumi0721debianarmhf/debian-armhf-dev:latest
```



----------------------------------------
#### Usage

* Run docker container and login.
    - Default user name : forumi0721



----------------------------------------
#### Docker Options

| Option             | Description                                      |
|--------------------|--------------------------------------------------|
| -                  | -                                                |


#### Ports

| Port               | Description                                      |
|--------------------|--------------------------------------------------|
| -                  | -                                                |


#### Volumes

| Volume             | Description                                      |
|--------------------|--------------------------------------------------|
| -                  | -                                                |


#### Environment Variables

| ENV                | Description                                      |
|--------------------|--------------------------------------------------|
| RUN_USER_NAME      | login user name (default:forumi0721)             |
| RUN_USER_UID       | login user uid (default:1000)                    |
| RUN_USER_GID       | login user gid (default:100)                     |



----------------------------------------
* [forumi0721debianx64/debian-x64-dev](https://hub.docker.com/r/forumi0721debianx64/debian-x64-dev/)
* [forumi0721debianaarch64/debian-aarch64-dev](https://hub.docker.com/r/forumi0721debianaarch64/debian-aarch64-dev/)
* [forumi0721debianarmhf/debian-armhf-dev](https://hub.docker.com/r/forumi0721debianarmhf/debian-armhf-dev/)

