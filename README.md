## Build the documentation website files

```sh
# install dependencies
pip install sphinx sphinx-autoapi sphinx-rtd-theme

# build docs
sphinx-build -b html source build 
```

Access the docs at `docs/build/index.html`.

For easy way to host the docs online, can try deploying using Github Pages.
