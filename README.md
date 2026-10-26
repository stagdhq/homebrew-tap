# Stagd's Homebrew tap

```bash
brew install stagdhq/tap/stagd
```

installs [`stagd`](https://github.com/stagdhq/stagd), Stagd's command line and relay, for macOS and Linux, as a cask: it's already built, so Homebrew doesn't need Xcode's Command Line Tools for it.

To update it: `brew upgrade stagdhq/tap/stagd`. Homebrew 6 and later leaves third-party taps out of a plain `brew upgrade`, and out of commands that don't name them in full, until you trust them; to have `brew upgrade` include stagd:

```bash
brew trust stagdhq/tap
```

`Casks/stagd.rb` is written by the [stagd repository's release workflow](https://github.com/stagdhq/stagd/blob/main/.github/workflows/release.yaml) for each release, from the release's checksums: don't edit it by hand.

Other ways to install, and what `stagd` does: [github.com/stagdhq/stagd](https://github.com/stagdhq/stagd).
