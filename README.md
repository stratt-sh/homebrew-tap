# stratt tap

Homebrew tap for [stratt](https://stratt.sh).

## Install

```sh
brew tap stratt-sh/tap
brew install stratt
```

## Migrating from zebpalmer/tap

If you installed stratt from the old `zebpalmer/tap`, use these steps to migrate:

```sh
brew uninstall stratt
brew untap zebpalmer/tap
brew install stratt-sh/tap/stratt
```

> **Note:** You must uninstall first — Homebrew will refuse to untap a tap
> while one of its formulae is still installed.
