# prysmaticlabs-docker-compose

Single docker-compose.yml for the ETH 2.0 test client by prylabs.net

## Prerequisites
- Docker compose installed
- An existing validator key (see https://prylabs.net/participate)

## Usage

1. Save `docker-compose.yml` from this repo, or clone the repo and copy the file to your prysm data directory
2. Open `docker-compose.yml` in editor, e.g. `nano docker-compose.yml` and replace `YOUR_KEY_PASSWORD`
3. Run `docker-compose up -d`
3. To view logs run `docker logs {CONTAINER_NAME}` (with `--follow` to keep the output running)
