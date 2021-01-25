# Ansible

## Installation

* Import the rootfs

``` sh
cat rootfs | podman import - ansible
```

* Build the dockerfile

``` sh
podman build -t ansible .
```
