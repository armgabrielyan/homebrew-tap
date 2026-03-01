# Homebrew Tap for deadbranch

This is the official Homebrew tap for [deadbranch](https://github.com/armgabrielyan/deadbranch) — a CLI tool to clean up stale git branches safely.

## Installation

```bash
brew install armgabrielyan/tap/deadbranch
```

Or add the tap first:

```bash
brew tap armgabrielyan/tap
brew install deadbranch
```

## Build from Source

To build from the latest source code:

```bash
brew install --HEAD armgabrielyan/tap/deadbranch
```

## Usage

```bash
# List stale branches (older than 30 days)
deadbranch list

# Preview what would be deleted
deadbranch clean --dry-run

# Delete merged stale branches
deadbranch clean
```

## More Information

- [Main Repository](https://github.com/armgabrielyan/deadbranch)
- [Documentation](https://github.com/armgabrielyan/deadbranch#readme)
- [Releases](https://github.com/armgabrielyan/deadbranch/releases)

## License

MIT
