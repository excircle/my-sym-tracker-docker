# My Sym Tracker (Docker)

This repository contains Docker related materials for running the My-Sym-Tracker application in Docker.

# Table of Contents

| Folder | Description |
| - | - |
| docker-images | Contains all Dockerfiles required to building `docker-compose` application |

## Install Docker-Compose on MacOS

| Step | Process | Instructions |
| - | - | - |
| 0 | Install `brew` on your laptop | If it does not already exist, install the MacOS package manager `brew`. The following bash command can be utlized to install brew. <br/><br/>`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"` |
| 1 | Install `docker` using `brew` | The following command can be used to install "Docker Desktop" for MacOS:<br/><br/>`brew install --cask docker` |
| 2 | Verify `docker-compose` version | Docker-Compose version can be verified using the following command:<br/><br/>`docker-compose version` |