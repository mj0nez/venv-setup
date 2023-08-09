# venv-setup

In this repository ``Dependabot`` tracks updates of my most used packages. The requirements.in specified dependencies are monitored and per update a new PR is created.

As no secondary dependencies are checked for new versions, to update the whole environment use ``pip-compile``:

```bash
pip-compile requirements.in --upgrade
```
