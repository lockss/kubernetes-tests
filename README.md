## Introduction
This is an experimental internal project to bring up a small Kubernetes cluster using only Docker containers. At
this time, it is intended only for getting familiar with Kubernetes, and as a non-trivial example of Docker Compose.

## Usage
1. Install `docker` and `docker-compose`. On ArchLinux systems, run the following command:

    ```
    sudo pacman -Sy docker docker-compose
    ```

2. Run `docker-compose` in the directory containing the `docker-compose.yaml` file:

    ```
    cd kubernetes-test
    sudo docker-compose up
    ```

## References

* Original `docker-compose.yaml` file from a [Cloudgear blog](https://www.cloudgear.net/blog/2015/5-minutes-kubernetes-setup/);
  the changes in our version allow it to run using the latest etcd, Kubernetes, and Docker components.
