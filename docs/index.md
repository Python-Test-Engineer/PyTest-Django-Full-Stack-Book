# PyTest Django Fullstack

## Purpose of this book 

The original book 'PyTest Cookbook', [https://pytest-cookbook.com/](https://pytest-cookbook.com/), had a section for Django Testing. It is worth using this as an additional resource as it contains many useful section on testing with PyTest and Toolbox utilities.

Based on the scope of testing for Django, it seemed advantageous to create its own book.

Testing will be done with PyTest as the runner and using PyTest tests. However, some tests will be based on the UnitTestCase built into Django.

## Contents

### Review of Django Docs

We will go through each part of the Django Testing section in the docs to extract the useful components for our PyTest suite. The `pytest-django` library uses all the Django test features so we do not lose any functionality.

### PyTest

We move into using PyTest and cover:

- Set up of PyTest Django
- Overview of include apps
- Explore the core tests for models, views and forms
- Dive deeper into SQL Schema tests for the models
- Use Playwright for API testing
- Use Playwright for End To End testing
- Use of Factories and Mocks to support our testing

The PyTest Framework will be useable 'out of the box' with over a 100 templated tests for your use.
