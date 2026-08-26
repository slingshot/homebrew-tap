# Slingshot Homebrew tap

```sh
brew install slingshot/tap/sendfm
```

## Formulae

| Formula  | Description |
| -------- | ----------- |
| `sendfm` | Send and receive end-to-end encrypted files from the command line ([source](https://github.com/slingshot/bolter/tree/main/apps/cli)) |

`sendfm` ships as a pre-compiled binary for macOS and Linux on arm64 and x86_64.
Windows is not a Homebrew target — take the `windows-x64.zip` from the
[releases page](https://github.com/slingshot/bolter/releases) instead, or use
the installer at <https://send.fm/install.sh>.

## This repository is generated

`Formula/sendfm.rb` is written by
[`apps/cli/scripts/render-formula.ts`](https://github.com/slingshot/bolter/blob/main/apps/cli/scripts/render-formula.ts)
and overwritten by the release workflow in `slingshot/bolter` every time a
`v*.*.*` tag is pushed. **Edits made here are lost on the next release** — fix
the renderer instead.

Checksums are copied from the release's own `checksums.txt` rather than
recomputed, so they attest to the bytes that were actually uploaded.
