# py315t-wheels

Prebuilt free-threaded CPython 3.15 (`cp315t`) wheels — alongside matching `abi3` wheels for GIL builds — for open-source Python packages that do not yet publish `cp315t` wheels on PyPI.

Each GitHub Release publishes a flat package index (`index.html`) and `SHA256SUMS` compatible with `uv`:

```toml
[[tool.uv.index]]
name = "coverwatch-wheels"
url = "https://github.com/coverwatch-ai/py315t-wheels/releases/download/<tag>/index.html"
format = "flat"
explicit = true
```

## Published packages

- **`temporalio`** (MIT, built unmodified from upstream [`temporalio/sdk-python`](https://github.com/temporalio/sdk-python) release tags)
