# Common Libraries

This directory contains some supporting libraries such as error handling, file
system, and database for the Teaclave platform, or more general TEE system.

- `mayfail`: A crate to help manage chained error in Rust.
- `protected_fs_rs`: A userspace file system implementation secured by SGX.
- `rusty_leveldb_sgx`: A LevelDB implementation, making key-value database in
  SGX enclave possible.

