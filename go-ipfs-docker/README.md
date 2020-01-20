# go-ipfs in docker

Reference: https://github.com/ipfs/go-ipfs

## Start

`docker-compose up -d`

## Run command

`docker-compose exec go-ipfs ipfs <some-ipfs-command-and-args>`

Example: `docker-compose exec go-ipfs ipfs version`

or

`docker-compose exec go-ipfs sh`

Will attach with shell, then you could run `ipfs <some-ipfs-command-and-args>`
