# Cookiecutter Test2Learn.py

A [Cookiecutter](https://github.com/audreyr/cookiecutter) template for [Test2learn](https://github.com/wonderchang/test2learn) Python and its packages.

The generated project requires following prerequisites:

  * [Docker](https://docs.docker.com/install/) 18.09+
  * [make](http://ftp.gnu.org/gnu/make/) 3.81

## Quickstart

    cookiecutter https://github.com/wonderchang/cookiecutter-test2learn-python.git

The first prompt input `python_package` should be a PyPI package name with its [version specifier](https://www.python.org/dev/peps/pep-0440/#version-specifiers) (e.g. `flask=1.0.2`) which you want to learn. Empty string `''` is available which generates a pure Python Test2learn environment without any 3rd-party package installed.

## Features

  * Less depenencies, [make](https://www.gnu.org/software/make/) and [Docker](https://www.docker.com/) only
  * Multiple testing environments with different Python versions powered by [tox](https://tox.readthedocs.io/en/latest/)
  * [Pytest](https://docs.pytest.org/en/latest/) featuring to make testing easy to write

Environment variable `TEST` enable to test a specific module or method following the usage of [Pytest specifying test](https://www.python.org/dev/peps/pep-0440/#version-specifiers)

    TEST=tests/test_module.py::test_method make test

<!--
  vi:et:wrap:ts=2:sw=2
-->
