# zero2prod

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
```