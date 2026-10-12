# applesec-ipsw

- `fetch.yml` — resolve and download an IPSW, cached for the rest of the run
- `kernel.yml` — `ipsw kernel` for the kernelcache, `ipsw dyld` when the shared cache is needed too
- `diff.yml` — one component across two builds

Artifacts only. Nothing binary gets committed, and retention is short on purpose.

Not affiliated with Apple. Apple binaries, and anything derived from them, are outside this repo
and outside its license.

# License

Apache-2.0, see `LICENSE`