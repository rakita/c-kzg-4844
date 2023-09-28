# Rust bindings

Generates the rust bindings for the c-kzg library.

Based on fbef59a3f9e8fa998bdb5069d212daf83d586aa5 commit from [`ethereum/c-kzg-4844`](https://github.com/ethereum/c-kzg-4844) repo.

## Build

```
cargo build --release
```

Build with `--features="minimal-spec"` to set the `FIELD_ELEMENTS_PER_BLOB`
compile time parameter to the pre-determined minimal spec value.

## Test

```
cargo test --release
```

## Benchmark

```
cargo bench
```
