# Python Project Template

## Purpose
This is a base template used for python projects. It uses a 'src' structure and contains commonly used directories and files.

It is meant to be portable and set up tools to improve code health.

## Setup
This project template can be used as is but for further setup and system integration, a setup script is included in `/dev/`. Depending on the coding environment, `setup_dev_dependencies.sh` or `SetupDevDependencies.ps1` can be used. Both scripts have the same behaviour, which is as follows:
1. Update pip
2. Install [the Poetry package](https://python-poetry.org/), a dependency management and packaging tool for Python
3. Install the pre-commit hook to the current .git.

## Supported Development Environment
This project template is IDE agnostic, it can be easily ported into any development environment.

With that said, the template includes a `.idea` directory, used by IntelliJ IDEs. This folder contains code style defaults which are in line with the `.pylintrc` file. If one is not using an IntelliJ IDE or wishes to set up their own project defaults, the `.idea` directory can be deleted.

## Attribution
* `.pylintrc`: The pylint file is authored by the maintainers of [the pyguide](https://google.github.io/styleguide/pyguide.html) from [the Google-originated open-source style guides repository](https://github.com/google/styleguide).
* `.idea/.gitignore`: The `.gitignore` file used for PyCharm is authored by the maintainers of [the JetBrains.gitignore file](https://github.com/github/gitignore/blob/main/Global/JetBrains.gitignore).
