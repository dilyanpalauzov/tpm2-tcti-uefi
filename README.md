[![Linux Build Status](https://travis-ci.org/tpm2-software/tpm2-tcti-uefi.svg?branch=master)](https://travis-ci.org/tpm2-software/tpm2-tcti-uefi)
[![Coverage Status](https://coveralls.io/repos/github/tpm2-software/tpm2-tcti-uefi/badge.svg?branch=master)](https://coveralls.io/github/tpm2-software/tpm2-tcti-uefi?branch=master)

# Overview
This is an implementation of a TCTI module for use with the TCG TPM2
Software Stack (TSS2) in the UEFI environment. This library is built as a
static archive `libtss2-tcti-uefi.a` suitable for linking with UEFI
applications.

# Build and Installation Instructions
Instructions to build and install `libtss2-tcti-uefi.a` are available in
the [INSTALL](INSTALL.md) file.

# Source Layout
├── example - sample code using UEFI TCG2 protocol and tpm2-tss libraries  
├── src  - source code and headers for `libtss2-tcti-uefi.a`  
└── test - unit tests

# Getting in Touch
If you're looking to discuss the source code in this project or get some
questions answered you should join the 01.org TPM2 mailing list:
https://lists.01.org/mailman/listinfo/tpm2.
We also have an IRC channel set up on [FreeNode](https://freenode.net/)
called \#tpm2.0-tss.

# Test Cases
Test strategy and cases are documented in [docs/test.md](docs/test.md).

# Examples
Several example UEFI executables are provided for reference and documented
in [docs/example.md](docs/example.md).
