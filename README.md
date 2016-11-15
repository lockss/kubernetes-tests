## Introduction
This is an experimental project to bring up a small Kubernetes cluster using only Docker containers. At
this time, it is intended only for getting familiar with Kubernetes.

## Usage
1. Install `docker` and `docker-compose`. On ArchLinux systems, run the following command:

    ```
    sudo pacman -Sy docker docker-compose
    ```

2. Run `docker-compose` in the directory containing the `docker-compose.yaml` file:

    ```
    cd kubernetes-test
    docker-compose up
    ```
