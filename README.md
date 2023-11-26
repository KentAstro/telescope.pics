# telescope.pics

[![Build](https://img.shields.io/github/checks-status/smkent/telescope.pics/main?label=build)][gh-actions]
[![GitHub stars](https://img.shields.io/github/stars/smkent/telescope.pics?style=social)][repo]

## Development

### [Poetry][poetry] installation

Via [`pipx`][pipx]:

```console
pip install pipx
pipx install poetry
pipx inject poetry poetry-dynamic-versioning poetry-pre-commit-plugin
```

Via `pip`:

```console
pip install poetry
poetry self add poetry-dynamic-versioning poetry-pre-commit-plugin
```

### Development tasks

#### Project setup

* Setup: `poetry install`
* Run static checks: `poetry run poe lint` or
  `poetry run pre-commit run --all-files`

#### Site development

* Start the live-reloading docs server: `poetry run mkdocs serve`
* Build the documentation site: `poetry run mkdocs build`

---

Created from [smkent/cookie-python][cookie-python] using
[cookiecutter][cookiecutter]

[cookie-python]: https://github.com/smkent/cookie-python
[cookiecutter]: https://github.com/cookiecutter/cookiecutter
[gh-actions]: https://github.com/smkent/telescope.pics/actions?query=branch%3Amain
[mkdocs]: https://www.mkdocs.org
[pipx]: https://pypa.github.io/pipx/
[poetry]: https://python-poetry.org/docs/#installation
[repo]: https://github.com/smkent/telescope.pics
