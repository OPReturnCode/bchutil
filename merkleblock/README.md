merkleblock
=====

[![Build Status](https://github.com/gcash/bchutil/actions/workflows/main.yml/badge.svg?branch=master)](https://github.com/gcash/bchutil/actions/workflows/main.yml)
[![ISC License](http://img.shields.io/badge/license-ISC-blue.svg)](http://copyfree.org)
[![GoDoc](http://img.shields.io/badge/godoc-reference-blue.svg)](http://godoc.org/github.com/gcash/bchutil/bloom)

Package merkleblock provides an API for creating and validating SPV proofs. An SPV proof
is a cryptographic proof that a given transaction is contained in the block. Instead of the
prover providing the full block he can provide the much smaller SPV proof.

## Installation and Updating

```bash
$ go get -u github.com/gcash/bchutil/merkleblock
```

## License

Package merkleblock is licensed under the [copyfree](http://copyfree.org) ISC
License.
