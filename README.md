# Development Environment with DevContainer

This project provides a pre-configured development environment using **DevContainer**, based on a Python Docker image with TensorFlow and Jupyter pre-installed. It is ideal for projects requiring GPU processing and deep learning.

[alt text](nvidia-smi.png)
![alt text](../juanmcristobal.github.io/assets/img/dev-containers.png)

## Environment Features

- Based on the `tensorflow/tensorflow:2.17.0-gpu-jupyter` image.
- GPU support enabled (requires NVIDIA Docker).
- Pre-configured non-root user (`vscode`) with `sudo` privileges.
- Ready-to-use configuration with VS Code and installed extensions:
  - Python
  - Jupyter!

## Included Files

- **`Dockerfile`**: Contains the configuration to build the Docker image.
- **`.devcontainer/devcontainer.json`**: Configures the remote development environment.

## Prerequisites

Before starting, ensure you have the following installed on your machine:

1. [Docker](https://www.docker.com/)
2. [NVIDIA Container Toolkit](https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/install-guide.html) (for GPU support)
3. [Visual Studio Code](https://code.visualstudio.com/)
4. [Remote - Containers Extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)

## Setup

### 1. Clone the Repository

Clone this repository to your local machine:

```bash
git clone <REPOSITORY_URL>
cd <REPOSITORY_NAME>
