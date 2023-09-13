# Hardhat Concurrency Issue

Demo repository for this issue: [https://github.com/NomicFoundation/hardhat/issues/4382](https://github.com/NomicFoundation/hardhat/issues/4382)

# Installation

```bash
$ yarn
```

# Steps to reproduce

```bash
$ yarn clean
$ yarn compile:error
```

Run both commands several times until it fails

You can also run:

```bash
$ yarn compile:success
```

To see that it works fine when concurrency is not used in Lerna
