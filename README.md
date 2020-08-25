# py-code-sanity

Config files used for Python code projects related to formatting, linting and docstyles.
Comes with good dose of personal preferences (especially related to formatting).

## Included Configurations

- `.pylintrc` is responsible for all things related to [pylint](https://www.pylint.org/) 
- `setup.cfg` is responsible for:
  - config of [YAPF](https://github.com/google/yapf) - the formatter
  - config of [flake8](https://flake8.pycqa.org/en/latest/) - the tool for style guide enforcement
  - config of [pydocstyle](https://pypi.org/project/pydocstyle/) - the tool for checking compliance with Python docstring conventions
  - config of any other tools that may be used in addition to the above for specific projects
