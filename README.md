JsonSDK - Graph
===============

Graph database as a service. Compatible with [Blueprint](https://github.com/tinkerpop/blueprints)

## Features

- Graph API (port: 8080)
- Administration UI (port: 8090)
- Out-of-box integrated with Azure Table Storage, RethinkDB, MySQL

## Pre-requisites
- Docker [1.2.x](https://docs.docker.com/#installation-guides) installed
- Fig [0.5.x](http://www.fig.sh/) installed

## Usage

```bash
docker run --rm -it -p 8080:8080 8090:8090 -v ~/jsonsdk/graph:/data jsonsdk/one-graph:latest
```

## Development

```bash
git clone git@github.com:jsonsdk/one-graph.git
cd one-graph
fig up
```
