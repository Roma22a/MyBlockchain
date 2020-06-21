# MyBlockchain
A simple Blockchain from [this tutorial](https://hackernoon.com/learn-blockchains-by-building-one-117428612f46?ref=hackernoon.com)

## Installation

```bash
# clone the repo
$ https://github.com/Roma22a/MyBlockchain.git

$ cd MyBloclchain

# install the dependencies
$ pip install -r requirements.txt

# Fire up the server:
$ python blockchain.py
# Listening on localhost:5000
```

## Routes

- `/mine (GET)` - the Mining Endpoint.
- `/transactions/new (POST)` - create a new transaction.
- `/nodes/register (POST)` - accept a list of new nodes in the form of URLs.
- `/nodes/resolve (GET)` - implement the Consensus Algorithm.
- `/chain (GET)` - returns the full Blockchain.
