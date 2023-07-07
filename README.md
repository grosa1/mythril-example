# Run Mythril
```
# setup
conda create -n sc-analysis python=3.8
conda activate sc-analysis
python3 -m pip install mythril

# run
git clone https://github.com/grosa1/mythril-example.git
cd mythril-example
npm i
myth analyze contracts/NFTAuction.sol --solc-json remapping.json
```

# NFT Auction

An interesting chalenge for creating an auction for a custom NFT.

## Prerequisites

In order to install, test and run the project you will need the following:
- [Docker](https://www.docker.com/products/docker-desktop/)
- [Node](https://nodejs.org/en/download)
- [Truffle](https://trufflesuite.com/docs/truffle/how-to/install/)

## TEST

### Locally

Locally we will test using ganache, to do that run following commands:
```sh
docker-compose -f docker-compose up -d
```

After waiting for ganache start you cna ru nthe tests: 
```sh
truffle test
```

###  Network Ropsten 
[WIP]


