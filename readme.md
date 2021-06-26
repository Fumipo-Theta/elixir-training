# Elixir training

Documents on overview of Elixir syntax and exercises providing playground on Jupyter notebooks.

We use [IElixir](https://github.com/pprzetacznik/IElixir) as jupyter kernel implementation for elixir.
See the latest definition of [docker image](https://github.com/pprzetacznik/IElixir/tree/master/docker/ielixir-requirements) about the available version of Erlang and Elixir.

## Requirements

- [Docker](https://www.docker.com/)
- [docker-compose](https://docs.docker.com/compose/)

## Launch jupyter server

Use Docker in local.

### Run container

- Build image and launch the container
  - `cd docker`, then `docker-compose up`
- Access to http://localhost:8888
- Notebooks are in [`notebook`](./notebook) directory

### Contributing guide

- Do not forget clear all output of the notebook before commit
