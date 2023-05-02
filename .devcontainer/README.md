# Local pyspark development environment

## Prerequisites

- Docker engine
- Docker compose
- Python and pyspark module

## How to run

- Clone the repository
- Build the image

```shell
cd BigDataAnalytics
docker build -t local_spark .
```

- Install the VSCode extension `Remote - Containers`
- VSCode: Open the folder and press `Ctrl+Shift+P` and select `Dev Container: Rebuild and Reopen in Container`, this will start the container and install the required dependencies and also mount the current folder inside the container, so you can edit the files locally and run them inside the container.
