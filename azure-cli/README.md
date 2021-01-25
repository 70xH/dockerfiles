# Azure-CLI

## Installation

* Import the rootfs

``` sh
cat rootfs | podman import - azure-cli
```

* Build the dockerfile

``` sh
podman build -t az .
```
