# Node And Postgres Dev Container

Based on the `javascript-node-postgres` template in the `src` directory at:

- https://github.com/devcontainers/templates

## Start Up Instructions

- Set up docker desktop and have it running.
- Open present directory with VSCode that has the dev container extension.
- press Ctrl-Shift-p and select `reopen in container` to start all containers.
- press Ctrl-Shift-p and select `attach to running container` and select db.
  - open terminal and run `psql -U postgres postgres` to start the pg cli.
