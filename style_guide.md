# Style Guide

## Basics

Automatic code formatters can save you tons of time and they make it easy for
collaborative projects to have consistent code formatting.

- Use [Black](https://github.com/psf/black) and
[Pylint](https://pylint.pycqa.org/en/latest/) for Python.
- Use [styler](http://styler.r-lib.org/) and
[linter](https://github.com/jimhester/lintr) for R.
- Use [Prettier](https://prettier.io/) for HTML, JavaScript, and CSS.

Use default settings in all cases
(except [setting Pylint to work with Black](https://black.readthedocs.io/en/stable/guides/using_black_with_other_tools.html#pylint)).

All are easily
(or natively) integrated into VS Code. The R packages are also easily
integrated into R Studio.

## Additional Rules

There are some things that the automated tools can't handle themselves.
A few additional things to be consistent about are listed below. They all
follow the most commonly used style guides for each language
(though they are sometimes more specific, e.g., for R variable names).

## Python and R

These adhere to [PEP8](https://peps.python.org/pep-0008/) and
the [tidyverse style guide](http://style.tidyverse.org/).

### Identifiers

- `ClassName`
- `variable_name`
- `function_name`
- `CONSTANT_VALUE`

## Javascript

These adhere to the [Airbnb style guide](https://airbnb.io/javascript/).

- Use `const` or `let` as appropriate. Don't use `var`.
- Use dot notation for accessing properties, not bracket notation, when possible.
- Use `===` and `!==` instead of `==` and `!=`.
- Start all comments with a space after the `//`.

### Identifiers

- `ClassName`
- `objectName`
- `functionName`
