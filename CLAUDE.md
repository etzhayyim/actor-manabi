# manabi repository guidance

This is an independent west-managed actor repository. Do not restore paths under
the former `20-actors` root.

- Treat EDN as canonical. JSON belongs only below `wire/` for external protocols.
- Put runtime namespaces below `src/manabi` and tests below `test/manabi`.
- Do not add Go, TinyGo, Python cell runtimes, wasm build products, or shell test
  runners.
- Preserve the G1–G14 education gates and actor-owned ADR/identity history.
- Run `kbb -M:test`, EDN parsing, JSON validation, and deprecated-artifact audits
  before publishing.
