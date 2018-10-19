# Microservice-Relation Service

This is the Microservice-Relation service

Generated with

```
micro new github.com/magicsupery/microservice-relation --namespace=go.micro --type=srv
```

## Getting Started

- [Configuration](#configuration)
- [Dependencies](#dependencies)
- [Usage](#usage)

## Configuration

- FQDN: go.micro.srv.microservice-relation
- Type: srv
- Alias: microservice-relation

## Dependencies

Micro services depend on service discovery. The default is consul.

```
# install consul
brew install consul

# run consul
consul agent -dev
```

## Usage

A Makefile is included for convenience

Build the binary

```
make build
```

Run the service
```
./microservice-relation-srv
```

Build a docker image
```
make docker
```# microservice-relation
