# Upstream and maintenance review

Independent maintenance of `remark-frontmatter@4.0.1` as `@stackline/remark-frontmatter`.

- Source history: https://github.com/remarkjs/remark-frontmatter/tree/bb147f9b6a67198a9579735a6e8b2dcd3103a61d
- Original npm integrity: `sha512-38fJrB0KnmD3E33a5jZC/5+gGAC2WKNiPw1/fdXJvijBlhA7RCsvJklrYJakS0HedninvaCYW8lQGf9C918GfA==`.
- Issues checked: 2026-09-29T00:22:04.858035+00:00.
- Original authors, notices and license are retained. Published runtime and declaration file hashes are recorded in `.stackline/upstream.json`; reviewed differences are explicitly listed there.
- Original functional suites run against both source and the extracted final tarball. Type checks and the complete development/runtime audit must pass.

## Issue triage

The bounded open-issue query returned no issue entries. This is not evidence that the upstream is abandoned or bug-free. No upstream runtime bug fix is claimed.

Historical snapshots were checked against an independently installed exact original npm package before refresh. All fixtures retain differential AST and serialization checks against that original package.

The evidence query fetched the latest 100 open and 30 closed issue/PR entries and removed PRs. This is a bounded review, not a claim of exhaustive issue history or resolution of every issue.

## Release verification

GitHub Actions publishes the reviewed passing-CI tarball. Release completion requires exact source identity, zero open CodeQL alerts, npm provenance and tarball identity, normal and aliased installs, and matching immutable GitHub release assets. Existing versions are never replaced.
