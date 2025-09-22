# Contibution Guide

To build and test:

1. Install OPAM following its instructions.
2. Install dependencies: `opam install --deps-only .`.
3. Compile Sail: `make`.
4. Install it (optional): `make install`.
5. Run all tests: `make test`. You can also `make c-test` to just run C tests.

# Submitting a PR

Format your code using

    dune fmt

To make this automatic run

    echo "dune fmt" > .git/hooks/pre-commit
