# Contributing to Glace

Thanks for your interest in contributing! This is the organization-wide
default guide; repositories with their own `CONTRIBUTING.md` (notably
[glacedb/glace](https://github.com/glacedb/glace/blob/dev/CONTRIBUTING.md))
take precedence — read the repo-local guide first.

## The short version

1. **Fork** the repository and create a branch off the default branch
   (`dev` where it exists).
2. **Make your change**, matching the surrounding code style. For Rust
   repositories the CI gate is: `cargo fmt --all -- --check`,
   `cargo clippy --workspace --all-features --all-targets -- -D warnings`,
   build, tests, doctests, and rustdoc with warnings denied.
3. **Pair every bug fix with a regression test** that fails before the fix
   and passes after.
4. **Use Conventional Commits** (`fix:`, `feat:`, `docs:`, …).
5. **Open a pull request** against the default branch with a clear
   description of the problem and the approach.

## Ground rules

- Be respectful and constructive — see our
  [Code of Conduct](CODE_OF_CONDUCT.md).
- Significant features are best discussed in an issue before you build them,
  so we can agree on direction and avoid wasted work.
- Never include credentials, customer data, or generated artifacts in a PR.
- Security issues go through [SECURITY.md](SECURITY.md), not public issues
  or PRs.
