# Homebrew Tap for armgabrielyan CLI tools

This tap publishes Homebrew formulas for the CLI tools maintained under `armgabrielyan`.

## Installation

```bash
brew tap armgabrielyan/tap
```

Then install any formula from the tap:

```bash
brew install armgabrielyan/tap/<formula>
```

## Available Formulas

- `autoloop`: agent-agnostic iterative optimization CLI
- `deadbranch`: clean up stale git branches safely
- `primer`: AI-guided project recipes and milestone workflows

Examples:

```bash
brew install armgabrielyan/tap/autoloop
brew install armgabrielyan/tap/deadbranch
brew install armgabrielyan/tap/primer
```

## Build from Source

To build the latest source version of a formula:

```bash
brew install --HEAD armgabrielyan/tap/<formula>
```

## More Information

- Browse formulas in the [`Formula/`](./Formula) directory.
- Each formula points to its upstream repository and release artifacts.

## License

MIT
