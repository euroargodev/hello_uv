# hello_uv

A simple Python project to learn how to use uv for dependency management, testing, and CI.

### 1. Create the project

```bash
uv init hello_uv
cd hello_uv
```

### 2. Test the entry point

```bash
uv run hello-uv
```

Runs the project.

### 3. Add development dependencies

```bash
uv add --dev pytest
```

Adds pytest to the `dev` dependency group.

### 4. Add project dependencies

```bash
uv add xarray numpy requests
```

Adds dependencies required by the project.

### 5. Run tests

```bash
uv run pytest
```

Runs the tests using the project's environment.