# playwright_crashed_lab
Try or crash playwright with Python/Node.js/Java/.Net

## to-do-list

* Host system is missing dependencies to run browsers.

## Prerequisites

* Python 3.8 or higher.
* Linux host such as Arch Linux, Debian, Ubuntu, RHEL ...etc
* [pyenv+poetry](https://setup_dev_environment.ootori.dev/computer%20languages/programming_languages/python/python/#usage-with-pyenvpoetry)
    * pyenv for Python versions control
    * poetry for Project dependency control
    * Project dependcy detialls will be in pyproject.toml/poetry.lock
* [Playwright for Python/Installation](https://playwright.dev/python/docs/intro)

## quick start

```shell
poetru shell
poetry add pytest-playwright
playwright install
cd src
pytest
```
