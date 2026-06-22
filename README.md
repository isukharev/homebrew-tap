# homebrew-tap

Homebrew tap for [`atl`](https://github.com/isukharev/atl) — a Git-style CLI for
Confluence & Jira, built for coding agents.

## Install

```sh
brew install isukharev/tap/atl
```

or, equivalently:

```sh
brew tap isukharev/tap
brew install atl
```

Then:

```sh
atl version
```

## Notes

- Prebuilt binaries for macOS and Linux (amd64 / arm64); no compilation.
- `Formula/atl.rb` is generated from each `atl` release's binaries with each
  platform's download URL pinned to its SHA-256
  (`scripts/gen-homebrew-formula` in the `atl` repo / `make homebrew`).
- Releases: <https://github.com/isukharev/atl/releases>.
