# Dolphin infrastructure configuration

This repository contains the configuration for Dolphin's various infrastructure
services -- some user facing, some developer facing.

This is a heavy WIP replacing https://github.com/dolphin-emu/sadm with a NixOS
based configuration.

## How to build

```shell
$ colmena build
```

## How to deploy

```shell
$ colmena apply
```

## TODO list of things to migrate

Old service configuration can be found in the historical `pre-nix` Git branch.

- buildbot
- changes poller
- fifoci
