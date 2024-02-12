# configure-ocp-pull-secrets

`configure-ocp-pull-secrets` is a bash script for configuring pull secrets for OpenShift Container Platform.

## Description

This script allows users to configure pull secrets for accessing container registries such as Quay and Docker Hub within
an OpenShift environment. It automates the process of logging in to these registries and setting up the necessary
authentication for accessing private repositories.

## Usage

```bash
./configure-ocp-pull-secrets [--quay-user <username> --quay-password <password>] [--docker-user <username> --docker-password <password>]
```

### Options

    --quay-user <username>: Quay username.
    --quay-password <password>: Quay password.
    --docker-user <username>: Docker Hub username.
    --docker-password <password>: Docker Hub password.

## Prerequisites

* The script requires either Podman or Docker to be installed on the system.
* Access to the OpenShift cluster where you want to configure the pull secrets.