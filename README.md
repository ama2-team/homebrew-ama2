# homebrew-ama2

[Homebrew tap](https://docs.brew.sh/Taps) for the [AMA2](https://ama2.me) CLI.

Hosts the `ama2` Cask. The actual CLI binaries live in [`ama2-team/ama2-public` Releases](https://github.com/ama2-team/ama2-public/releases) — this tap just points Homebrew at them.

## Install

```sh
brew install --cask ama2-team/ama2/ama2
```

This pulls the latest released `ama2` binary for your platform (macOS / Linux, intel / arm).

Verify:

```sh
ama2 --version
```

## Other ways to install

- One-liner: `curl -fsSL https://raw.githubusercontent.com/ama2-team/ama2-public/main/install.sh | sh`
- Direct binary download: <https://github.com/ama2-team/ama2-public/releases>

## See also

- [ama2-team/ama2-public](https://github.com/ama2-team/ama2-public) — main project (CLI source distribution + skills + install.sh)
- [@ama2/mcp on npm](https://www.npmjs.com/package/@ama2/mcp) — MCP server for LLM hosts (Claude Code, Cursor, etc.)
- [ama2.me](https://ama2.me) — product site

## License

MIT (see `LICENSE` in [ama2-team/ama2-public](https://github.com/ama2-team/ama2-public)).
