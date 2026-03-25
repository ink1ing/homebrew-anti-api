# homebrew-anti-api

Homebrew tap for [Anti-API](https://github.com/ink1ing/anti-api).

## Install

```bash
brew tap ink1ing/anti-api
brew install anti-api
```

## Upgrade

```bash
brew upgrade anti-api
```

## Run

```bash
anti-api
```

## Notes

- The formula installs Bun dependencies and prebuilds the Rust proxy during `brew install`.
- In-app self-update is disabled for Homebrew-managed installs. Use `brew upgrade anti-api` instead.
- Formula source of truth: `Formula/anti-api.rb` from the main Anti-API repository.
