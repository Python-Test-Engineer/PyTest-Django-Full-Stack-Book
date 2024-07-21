# Set up

## Install Pytest

`pip install pytest-django`

## Add pytest.ini

Add to pytest.ini

`DJANGO_SETTINGS_MODULE = studybud.settings` where `studybud` is name of root app where settings.py resides.

## Add log folder

`pytest.ini` is configured to set up logging to this folder. 

Location can be changed.

## Config setup

This is a convenience utility and not required.

The `config` folder and `utils/read_config.py` can be used to read config settings in the config folder.

## Remove test.py

To avoid conflicts that I have encountered, remove all test.py files in any apps and use tests folder.

## Test set up

Run `python -m pytest -vs` and all tests in `tests/01_setup` folder should pass for setup, logging and config.

Logging will register some events.

`read_config.py` should also pass.

<br>