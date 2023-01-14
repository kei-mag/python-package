# Python package "mypackage"

## Let's get started!

**First, you should create a directory in the src directory with the name to be used during import like 'mypkg'.**

### Directory structure
**src-layout**
```
package_root
├── pyproject.toml
├── ...
└── src/
    └── mypkg/
        ├── __init__.py
        ├── ...
        ├── module.py
        └── subpkg1/
            ├── __init__.py
            ├── ...
            └── module1.py
```


## To upload package to PyPI
If you would like to upload this package to pypi.org or test.pypi.org, you must set the API key for test.pypi.org as TEST_PYPY_API and the API key for pypi.org as PYPY_API in the GitHub Actions Secret.
