# aws-sigv4

Low-level SigV4 request signing implementations. Customers will not generally need to use this crate directly. If you
need to manually sign requests, [aws-sig-auth](https://crates.io/crates/aws-sig-auth) offers a higher level interface
for signing.

<!-- anchor_start:footer -->
This crate is part of the [AWS SDK for Rust](https://awslabs.github.io/aws-sdk-rust/) and the [smithy-rs](https://github.com/awslabs/smithy-rs) code generator. In most cases, it should not be used directly.
<!-- anchor_end:footer -->

# Additional details

Forked from [smithy-rs](https://github.com/awslabs/smithy-rs) (official aws rust SDK) - to support wasm32 compilation targets.

Source code based on release tag [release-2023-08-22](https://github.com/awslabs/smithy-rs/releases/tag/release-2023-08-22).
