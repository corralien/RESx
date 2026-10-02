# Installation

## Requirements

RESx requires:

* Python 3.12 or later
* [uv](https://docs.astral.sh/uv/) for Python environment and dependency management

[yEd](https://www.yworks.com/products/yed) is required for the visualization steps described in [HOWTO.md](HOWTO.md).

## Clone the repository

Clone the RESx repository and enter the project directory:

```bash
git clone <repository-url>
cd RESx
```

## Install RESx

Using `uv`:

```bash
uv sync
```

This creates a virtual environment and installs RESx together with its dependencies.

Activate the virtual environment:

```bash
source .venv/bin/activate
```

Check that the `resx` command is available:

```bash
resx --help
```

For an example of how to use RESx, see [HOWTO.md](HOWTO.md).

