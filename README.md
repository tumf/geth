# geth

    https://github.com/ethereum/go-ethereum

### Basic usage

    sudo docker run -v /path/to/data:/data quay.io/tumf/geth

### Mine

create account (only once at first)

    sudo docker run -v /path/to/data:/data quay.io/tumf/geth account new

mine

    sudo docker run -v /path/to/data:/data quay.io/tumf/geth --mine

### use rpc from other container

    sudo docker run -v /path/to/data:/data --name geth quay.io/tumf/geth

    sudo docker run --net container:geth YourApp





