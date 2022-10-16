# zero2prod
[![Rust](https://github.com/whatrocks/zero2prod/actions/workflows/general.yml/badge.svg)](https://github.com/whatrocks/zero2prod/actions/workflows/general.yml) [![Security audit](https://github.com/whatrocks/zero2prod/actions/workflows/scheduled-audit.yml/badge.svg)](https://github.com/whatrocks/zero2prod/actions/workflows/scheduled-audit.yml)

project from book "zero to production in rust"

## useful commands

```bash
# run commands on save
cargo watch -x check -x text -x run

# lint and fail if isses
cargo clippy -- -D warnings

# format check
cargo fmt -- --check

# check for known security issues
cargo audit

# expand macros
cargo +nightly expand
```