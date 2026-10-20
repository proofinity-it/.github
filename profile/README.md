# Proofinity

**Proved, not just plausible.** We build tools on formal methods: give
something an exact meaning in Lean, and let a proof checker say what holds.

- **declbuild** — mathematics without a center. It builds and checks Lean one
  declaration at a time and gives each one an address computed from its
  content. Coming soon.
  [proofinity.it/mathematics](https://proofinity.it/mathematics)
- **polis** — formal verification for COBOL. It reads a COBOL estate into a
  formal model in Lean, then explains it, assesses it and transforms it with
  changes proven to preserve behaviour. It runs on your own machines.
  [proofinity.it/polis](https://proofinity.it/polis)

## Open source

The pieces underneath are public, under Apache-2.0:

- [**CA**](https://github.com/proofinity-it/CA) — content-addressed identity
  for Lean 4 declarations: a SHA-256 address derived from what a declaration
  says, not from its name, file or project.
- Lean bindings to C libraries:
  [redis-lean](https://github.com/proofinity-it/redis-lean) ·
  [arrow-lean](https://github.com/proofinity-it/arrow-lean) (Arrow and Parquet) ·
  [kafka-lean](https://github.com/proofinity-it/kafka-lean) ·
  [curl-lean](https://github.com/proofinity-it/curl-lean) ·
  [libsodium-lean](https://github.com/proofinity-it/libsodium-lean) ·
  [zlog-lean](https://github.com/proofinity-it/zlog-lean)

Issues and pull requests are welcome.

## Get in touch

[proofinity.it](https://proofinity.it) · info@proofinity.it ·
[LinkedIn](https://www.linkedin.com/company/proofinity-it)

Proofinity s.r.l. — Milan, Rome (Italy)
