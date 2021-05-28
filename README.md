# matlab-project-template [![CI](https://github.com/ssciwr/matlab-project-template/actions/workflows/ci.yml/badge.svg)](https://github.com/ssciwr/matlab-project-template/actions/workflows/ci.yml)
Basic template to start your Matlab research software development

The main functionality is implemented in the `adder` package.

Each function `X` is implemented in the file `X.m`, and tests for that function are placed in `test_X.m`.

Currently the only function is `addOne`.

The script `main.m` uses this `adder` package.

When a pull request is opened with a change to this repository, CI jobs run the main script and all the tests using Matlab and Octave.