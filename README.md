# Python Docs Sphinx Theme (UBS Edition)

Forked from https://github.com/python/python-docs-theme

The Sphinx theme for the [UNICORN Binance Suite](https://github.com/oliver-zehentleitner/unicorn-binance-suite) documentation.

## Installation

```
pip install python-docs-theme-ubs
```

https://pypi.org/project/python-docs-theme-ubs

## Usage

Settings for `source/conf.py`:

```python
html_theme = 'python_docs_theme_ubs'
html_context = {
    'github_repo_name': 'unicorn-binance-suite',
    'github_user_name': 'oliver-zehentleitner',
    'project_name': project,
}
```

### Elements are inherited by:
- https://github.com/sphinx-doc/sphinx/tree/master/sphinx/themes/default
- https://github.com/sphinx-doc/sphinx/tree/master/sphinx/themes/basic
