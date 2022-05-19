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