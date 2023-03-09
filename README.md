## Build the documentation website files

```sh
# install dependencies
pip install sphinx sphinx-autoapi sphinx-rtd-theme

# build docs
sphinx-build -b html source docs 
```

Access the docs at `docs/build/index.html`.

For easy way to host the docs online, can try deploying using Github Pages.

I used the workflow described in: https://coderefinery.github.io/documentation/gh_workflow/
