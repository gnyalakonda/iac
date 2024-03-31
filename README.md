# IAC

Infrastucture as code to install jenkins using reverse proxy with SSL support

## Prerequisites
1. Install the docker
2. Make sure ports 80, and 443 are available

## Installation

Download the source code from git.

```bash
git clone git@github.com:gnyalakonda/iac.git
```

## Usage

```bash
cd iac
git fetch origin jenkins-docker-compose-basic
git checkout jenkins-docker-compose-basic 
docker-compose up
```

Open the browser and go to [https://localhost/jenkins](https://localhost/jenkins).

