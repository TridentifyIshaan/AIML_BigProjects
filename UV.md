# UV

An extremely fast Python package and project manager, written in Rust.

<p align="center">
  <img alt="Shows a bar chart with benchmark results." src="https://github.com/astral-sh/uv/assets/1309177/629e59c0-9c6e-4013-9ad4-adb2bcf5080d#only-light">
</p>

<p align="center">
  <img alt="Shows a bar chart with benchmark results." src="https://github.com/astral-sh/uv/assets/1309177/03aa9163-1c79-4a87-a31d-7a9311ed9310#only-dark">
</p>

<p align="center">
  <i>Installing <a href="https://trio.readthedocs.io/">Trio</a>'s dependencies with a warm cache.</i>
</p>

## Highlights

* A single tool to replace `pip`, `pip-tools`, `pipx`, `poetry`, `pyenv`, `twine`, `virtualenv`, and more.
* [10-100x faster](https://github.com/astral-sh/uv/blob/main/BENCHMARKS.md) than `pip`.
* Provides comprehensive project management, with a universal lockfile.
* Runs scripts, with support for inline dependency metadata.
* Installs and manages Python versions.
* Runs and installs tools published as Python packages.
* Includes a pip-compatible interface for a performance boost with a familiar CLI.
* Supports Cargo-style workspaces for scalable projects.
* Disk-space efficient, with a global cache for dependency deduplication.
* Installable without Rust or Python via `curl` or `pip`.
* Supports macOS, Linux, and Windows.

uv is backed by [Astral](https://astral.sh), the creators of [Ruff](https://github.com/astral-sh/ruff).

## Installation

Install uv with our official standalone installer:

**macOS and Linux**
```sh
$ curl -LsSf https://astral.sh/uv/install.sh | sh
```

**Windows**
```powershell
PS> powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

Then, check out the [first steps](getting-started/first-steps/) or read on for a brief overview.

> **Tip**
> uv may also be installed with pip, Homebrew, and more. See all of the methods on the [installation page](getting-started/installation/).

## Project Initialization

```sh
uv init
```

## Create Virtual environment

```sh
uv venv
```

## Activate Virtual environment

```sh
source .venv/bin/activate
```

## Install Libraries

### Independent

```sh
uv add libraryname
```

### From requirements.txt

```sh
uv add -r requirements.txt
```