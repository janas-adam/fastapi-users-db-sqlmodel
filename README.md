# FastAPI Users - Database adapter for SQLModel

<p align="center">
  <img src="https://raw.githubusercontent.com/frankie567/fastapi-users/master/logo.svg?sanitize=true" alt="FastAPI Users">
</p>

<p align="center">
    <em>Ready-to-use and customizable users management for FastAPI</em>
</p>

[![build](https://github.com/fastapi-users/fastapi-users-db-sqlmodel/workflows/Build/badge.svg)](https://github.com/fastapi-users/fastapi-users/actions)
[![codecov](https://codecov.io/gh/fastapi-users/fastapi-users-db-sqlmodel/branch/master/graph/badge.svg)](https://codecov.io/gh/fastapi-users/fastapi-users-db-sqlmodel)
[![PyPI version](https://badge.fury.io/py/fastapi-users-db-sqlmodel.svg)](https://badge.fury.io/py/fastapi-users-db-sqlmodel)
[![Downloads](https://pepy.tech/badge/fastapi-users-db-sqlmodel)](https://pepy.tech/project/fastapi-users-db-sqlmodel)
<p align="center">
<a href="https://github.com/sponsors/frankie567"><img src="https://md-btn.deta.dev/button.svg?text=Buy%20me%20a%20coffee%20%E2%98%95%EF%B8%8F&bg=ef4444&w=200&h=50"></a>
</p>

---

**Documentation**: <a href="https://fastapi-users.github.io/fastapi-users/" target="_blank">https://fastapi-users.github.io/fastapi-users/</a>

**Source Code**: <a href="https://github.com/fastapi-users/fastapi-users" target="_blank">https://github.com/fastapi-users/fastapi-users</a>

---

Add quickly a registration and authentication system to your [FastAPI](https://fastapi.tiangolo.com/) project. **FastAPI Users** is designed to be as customizable and adaptable as possible.

**Sub-package for SQLModel support in FastAPI Users.**

## Development

### Setup environment

[Hatch](https://hatch.pypa.io/1.12/) is a project management tool used for environments and dependencies.

Install needed dependencies:
```bash
hatch run pip install -e .
```

Get more information about [Hatch](https://hatch.pypa.io/1.12/):
```bash
hatch --help
```

### Run unit tests

To run all unit tests for the project execute:

```bash
hatch run test
```


There are quite a few unit tests, so you might run into ulimit issues where there are too many open file descriptors. You may be able to set a new, higher limit temporarily with:

```bash
ulimit -n 2048
```

### Format the code

Execute the following command to apply `isort` and `black` formatting:

```bash
hatch run lint
```

## License

This project is licensed under the terms of the MIT license.
