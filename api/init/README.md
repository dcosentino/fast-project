# Data import

## Install mongodb on oxs with Homebrew

- `brew install mongodb`
- `brew services start/stop/restart mongodb`
- `brew services list`

## Paths
- db: `/usr/local/var/mongodb/`
- config: `/usr/local/etc/mongod.conf`
- log: `/usr/local/var/log/mongodb/mongo.log`

## Authentication
TODO

## Init
- Make sure `init.sh` and `convert.py`,  are executable. If not just type `chmod +x <file>`
- Run `./init.sh`
    - Creates indexes in the database
    - Converts and imports the data



