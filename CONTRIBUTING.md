# Contributing to Magrathean UK Projects

Thank you for your interest in contributing to Magrathean UK projects!

## Developer Certificate of Origin (DCO)

To ensure clear intellectual property provenance, all contributions to open-source Magrathean repositories must include a Developer Certificate of Origin sign-off line in commit messages:

```text
Signed-off-by: Full Name <email@example.com>
```

You can sign commits automatically using `git commit -s`.

## Engineering Principles

1. **Local-First:** Prioritize local execution, on-device data storage, and deterministic offline behavior.
2. **Strict Licensing:** Ensure all third-party dependencies are permissively licensed (MIT, Apache-2.0, BSD). Copyleft dependencies (GPL/AGPL) are prohibited unless explicitly documented.
3. **Clean Code & Tooling:**
   - Rust: format with `cargo fmt`, lint with `cargo clippy -- -D warnings`, check with `cargo deny check`.
   - Swift: Swift 6 language mode, zero warnings, format with `swift-format`.
   - Python: format and lint with `ruff check` and `ruff format`.
   - TypeScript: pass `npm run typecheck && npm run lint`.
