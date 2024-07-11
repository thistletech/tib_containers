# Thistle-in-browser containers in WASM format

This is a repository served as storage for TIB containers. It's supposed to be
used as a submodule for the [tib-demo](https://github.com/thistletech/tib-demo)
repo.

Due to GitHub's per-file size limit, one needs to split a large image (e.g.,
`input.wasm`) into smaller chunks (e.g., 50MB):

```bash
# Split input.wasm into 50MB chunks
split -b 52428800 --additional-suffix .wasm -d input.wasm tib-1.1.1_
```

