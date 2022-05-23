## Install LocalJuno

1. Run the following commands::

```sh
$ git clone --depth 1 https://github.com/dawiddrzala/LocalJuno
$ cd LocalJuno
```

2. Make sure your Docker daemon is running in the background and [`docker-compose`](https://github.com/docker/compose) is installed.

## Start, stop, and reset LocalJuno

- Start LocalJuno:

```sh
$ docker-compose up
```

Stop LocalJuno:

```sh
$ docker-compose stop
```

Reset the world state:

```sh
$ docker-compose rm
```

## Accounts

LocalJuno is pre-configured with one validator

| Account   | Address                                                                                                  | Mnemonic                                                                                                                                                                   |
| --------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| validator | `juno1phaxpevm5wecex2jyaqty2a4v02qj7qmpjja9n`<br/>`junovaloper1phaxpevm5wecex2jyaqty2a4v02qj7qm70yj72` | `satisfy adjust timber high purchase tuition stool faith fine install that you unaware feed domain license impose boss human eager hat rent enjoy dawn`                    |