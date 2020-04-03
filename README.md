# bitcoin-docker-box
Personal docker-compose box with Bitcoin Core, Electrs and Tor hidden service.


## Usage

> It requires docker/docker-compose

* Run a box in mainnet

```sh
# First export to shell the environment variables
export BITCOIN_RPC_USER=user
export BITCOIN_RPC_PASSWORD=password
export BITCOIN_VOLUME=/my/absolute/path/to/volume
export ELECTRS_VOLUME=/my/absolute/path/to/other/volume

# Start the box
docker-compose up -d
```


