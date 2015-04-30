# zeitgeist/docker-whois

[whois](https://github.com/rfc1036/whois) in a Docker container.

## Requirements

* [Docker](https://www.docker.com/) 1.5+ (previous versions may work fine, but I haven't tried)

## Installation

Get the [trusted build on the docker hub](https://registry.hub.docker.com/u/zeitgeist/docker-whois/):

```bash
$ docker pull zeitgeist/docker-whois
```

or download and compile the source yourself from Github:

```bash
$ git clone https://github.com/alexzeitgeist/docker-whois.git
$ cd docker-whois
$ docker build -t zeitgeist/docker-whois .
```

## Usage

[whois](https://github.com/rfc1036/whois) is a command line whois client. Its internal database is frequently updated to include new domains.

Example usage:

```bash
$ docker run --rm zeitgeist/docker-whois zeitgeist.se
```
