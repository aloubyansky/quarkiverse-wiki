# Joining Quarkiverse

Projects hosted in the Quarkiverse organization on github should respect the following conventions and policies.

## Repository name

The repository name under the quarkiverse organization should have `quarkiverse-` prefix. This will help avoid potential conflicts when cloning and/or forking the repository.

## Project's Maven artifact `groupId`s

The Maven `groupId` of the project's artifacts should follow the following format: `io.quarkiverse.<project-name>`. In other words, the project’s `groupId` should start with the `io.quarkiverse.` prefix followed by the project-specific unique name in which dots aren't allowed.

## Root package name

The root package name is expected to be the same as the project’s Maven artifact `groupId`.

## LICENSE

The project is expected to be licensed under ASL 2.0. (TO BE CONFIRMED)