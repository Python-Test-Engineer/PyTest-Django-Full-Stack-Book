# Set up

## Installs

`pytest-django` installs `pytest`.

`playwright` used for E2E. Please note after installing `playwright` run `run playwright install` to load browsers.

`pytest-playwright`

`django-extensions` is a utility we use.

`rich` and `pyboxen` are used for console output.

`factory-boy` (installs `Faker`) for data generation.

## Add pytest.ini

Add to pytest.ini

`DJANGO_SETTINGS_MODULE = studybud.settings` where `studybud` is name of root app where settings.py resides.

## Add log folder 

*Optional*

`pytest.ini` is configured to set up logging to this folder. 

Location can be changed.

## Config setup

*Optional*

This is a convenience utility and not required.

The `config` folder and `utils/read_config.py` can be used to read config settings in the config folder.

## Remove test.py

To avoid conflicts that I have encountered, remove all test.py files in any apps and use tests folder.

## Test set up

Run `python -m pytest -vs` and all tests in `tests/01_setup` folder should pass for setup, logging and config.

Logging will register some events.

`read_config.py` should also pass.

<br>