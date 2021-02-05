# Rust action
This provides feel free Rust sandbox container.

# Example usage

```yml
on: [push]
jobs:
  do-something:
    runs-on: ubuntu-latest
    steps:
      - uses: mtwtkman/rust-action@master
      - name: Run test
        run: cargo test
```
