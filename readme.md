
# New Python Project

All boilerplate required for a new python project.
Includes.utomated Github testing.
Assumes the use of mypy and tox.

## After cloning

In a conda env

## Tests

Tests should be created in the "tests" directory.
All test files should start with "test_".
Default testing library is pytest.

## Requirements

User requirements should be listed in requirements.txt.
Dev requirements are listed in requirements_dev.txt.

## Env

Environment variables stored in .env.
Format is VARIABLE_NAME=VALUE

## Secrets

Service specific configs should be stored in secrets.json.
Format is {"Service 1": {"var1": "val"}, "Service 2" : ...}

## Setup.py

Leave as is.

## Setup.cfg

### Options/packages

Should contain a list of the packages in the src directory.

### [options.package_data]

Should contain a reference for each directory in the package.
Example is basic=py.typed
py.typed should be a blank file in each of these directories.

### Metadata URL

Should be a link to the project's repository
