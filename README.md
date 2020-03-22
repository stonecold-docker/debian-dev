# debian-dev

#### [debian-x64-dev](https://hub.docker.com/r/forumi0721debianx64/debian-x64-dev/)
![Docker Image Version (tag latest semver)](https://img.shields.io/docker/v/forumi0721debianx64/debian-x64-dev/latest)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/forumi0721debianx64/debian-x64-dev/latest)
![MicroBadger Layers (tag)](https://img.shields.io/microbadger/layers/forumi0721debianx64/debian-x64-dev/latest)
![Docker Pulls](https://img.shields.io/docker/pulls/forumi0721debianx64/debian-x64-dev)
![Docker Stars](https://img.shields.io/docker/stars/forumi0721debianx64/debian-x64-dev)
#### [debian-aarch64-dev](https://hub.docker.com/r/forumi0721debianaarch64/debian-aarch64-dev/)
![Docker Image Version (tag latest semver)](https://img.shields.io/docker/v/forumi0721debianaarch64/debian-aarch64-dev/latest)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/forumi0721debianaarch64/debian-aarch64-dev/latest)
![MicroBadger Layers (tag)](https://img.shields.io/microbadger/layers/forumi0721debianaarch64/debian-aarch64-dev/latest)
![Docker Pulls](https://img.shields.io/docker/pulls/forumi0721debianaarch64/debian-aarch64-dev)
![Docker Stars](https://img.shields.io/docker/stars/forumi0721debianaarch64/debian-aarch64-dev)
#### [debian-armhf-dev](https://hub.docker.com/r/forumi0721debianarmhf/debian-armhf-dev/)
![Docker Image Version (tag latest semver)](https://img.shields.io/docker/v/forumi0721debianarmhf/debian-armhf-dev/latest)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/forumi0721debianarmhf/debian-armhf-dev/latest)
![MicroBadger Layers (tag)](https://img.shields.io/microbadger/layers/forumi0721debianarmhf/debian-armhf-dev/latest)
![Docker Pulls](https://img.shields.io/docker/pulls/forumi0721debianarmhf/debian-armhf-dev)
![Docker Stars](https://img.shields.io/docker/stars/forumi0721debianarmhf/debian-armhf-dev)



----------------------------------------
#### Description

* Distribution : [Debian GNU/Linux](https://www.debian.org/)
* Architecture : x64,aarch64,armhf
* Appplication : -
    - Development environment



----------------------------------------
#### Run

```sh
docker run -i -t --rm \
           -e RUN_USER_NAME=<user_name> \
           -e RUN_USER_UID=<user_uid> \
           -e RUN_USER_GID=<user_gid> \
           forumi0721debian[ARCH]/debian-[ARCH]-dev:latest
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

