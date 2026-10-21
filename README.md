# lock-file-workflow

Test reusable GitHub Actions workflow used to exercise `gh actions-lock` lockfiles.

| Ref | Content |
|-----|---------|
| `v1.0.0` | prints `Hello world from V1` |
| `v2.0.0` | prints `Hello world from V2` + `actions/checkout@v7.0.1` |
| `v3.0.0` | prints `Hello world from V3` + `super-linter/super-linter/slim@v6.5.0` (known CVE) |
| `main` (unreleased) | prints `A wrong hello world` |
