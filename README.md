# ObaLabUtils

## Build Environment

### 1. install [uv](https://github.com/astral-sh/uv)

```zsh
# On macOS and Linux.
$ curl -LsSf https://astral.sh/uv/install.sh | sh

# On Windows.
$ powershell -c "irm https://astral.sh/uv/install.ps1 | iex"

# With pip.
$ pip install uv
```

### 2. create virtual enviroment

```zsh
uv sync
```

### 3. Activate virtual environment

```zsh
# On macOS and Linux.
. .venv/bin/activate
```
