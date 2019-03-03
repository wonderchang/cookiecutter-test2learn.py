# Test2learn Python{% if cookiecutter.python_package_project_name %} {{ cookiecutter.python_package_project_name }}{% endif %}

A [Test2learn](https://github.com/wonderchang/test2learn) project for understanding Python{% if cookiecutter.python_package_slug %} **[{{ cookiecutter.python_package_slug }}](https://pypi.org/project/{{ cookiecutter.python_package_slug }}/)**{% endif %}.

## Quickstart

Build running image

    make

Run tests to learn

    make test

Go to container inside to figure out something wrong if needed

    make shell

Clean artifects

    make clean


<!--
  vi:et:wrap:ts=2:sw=2
-->
