Near Fungible Token (FT)
===================

Example implementation of a [Fungible Token] contract which uses [near-contract-standards]. This is a contract-only example.

[Fungible Token]: https://nomicon.io/Standards/FungibleToken/Core
[near-contract-standards]: https://github.com/near/near-sdk-rs/tree/master/near-contract-standards

Prerequisites
=============

1. Make sure Rust is installed per the prerequisites in [`near-sdk-rs`](https://github.com/near/near-sdk-rs#pre-requisites)
2. Ensure `near-cli` is installed by running `near --version`. If not installed, install with: `npm install -g near-cli`

## Building

To build run:
```bash
./scripts/build.sh
```

Smart contract will get deployed to your NEAR account through NEAR CLI (command line interface).

more details: https://github.com/near/near-cli