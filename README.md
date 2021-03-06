# Cloudflare CLI [![Build Status](https://travis-ci.org/lucascaro/cloudflare-cli.svg?branch=master)](https://travis-ci.org/lucascaro/cloudflare-cli)

Simple Cloudflare CLI to help with common tasks.

## Installation

Install with pip:

```bash
pip install cfcli
```

Alternatively, clone this repository and install with pipenv.


## Usage

Run `cfcli --help` for up-to-date detailed usage.

## Examples

```bash

cfcli zone list #list all zones

cfcli purge-all my-domain.com #purge all cache for the zone my-domain.com

cfcli purge my-domain.com / #purge https://my-domain.com/

cfcli purge my-domain.com http://my-domain.com/some/path #purge single URL in the given zone

cfcli purge my-domain.com -f urls.txt #purge urls from urls.txt

```
