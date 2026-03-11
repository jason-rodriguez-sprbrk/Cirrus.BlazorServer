# Cirrus.BlazorServer (POC)

This repository is part of a proof-of-concept demonstrating how a shared component library can be integrated using **Git Subtree**.

The shared library lives in the following repository:

`Sprbrk.Poc.DesignLibrary`

It is embedded into this project using Git Subtree under:

```
src/design-library
```

The subtree allows the application to consume the component library directly while still allowing the library to exist as an independent repository.

For full documentation of the workflow, see the README in:

`Sprbrk.Poc.DesignLibrary`