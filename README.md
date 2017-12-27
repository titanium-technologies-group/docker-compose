# docker-compose

Bash script, which allow to use [docker/compose](https://github.com/docker/compose) as [docker image](https://hub.docker.com/r/docker/compose).

That script requires only standard nix tools and provides auto-updates, without additional dependencies


<!-- vim-markdown-toc GFM -->

* [Requirements](#requirements)
* [Installation](#installation)
* [Usage](#usage)
* [Updates](#updates)

<!-- vim-markdown-toc -->

## Requirements

* sed
* docker

## Installation

```bash
curl -o ~/bin/docker-compose -s https://raw.githubusercontent.com/titanium-codes/docker-compose/master/docker-compose && chmod +x ~/bin/docker-compose
```

> **NOTE**: You can download script in any location (which included in `$PATH`), but updater will try to edit script file when new docker-compose version will be released.
> That means, that you should have write permissions to target file, the best way is to place script in your home folder.

## Usage

Same as docker-compose

## Updates

Script will check updates every day, if new version will be released, script will update itself and download new docker/compose image
