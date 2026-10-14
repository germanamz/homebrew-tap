# germanamz/homebrew-tap

Homebrew tap for [tusk](https://github.com/germanamz/tusk), agent memory you can code-review.

```bash
brew install germanamz/tap/tusk
```

This installs the `tusk` binary, its man pages (`man tusk`) and bash, zsh and fish completions, on macOS and on Linux with Homebrew. Upgrade with `brew upgrade tusk`. `tusk update` recognizes a Homebrew install and points you back here instead of replacing the binary under brew.

`Casks/tusk.rb` is written by tusk's release workflow each time a release goes out, so edits made here get overwritten. Open issues and pull requests on [germanamz/tusk](https://github.com/germanamz/tusk) instead.

The release binaries are cosign-signed but not notarized by Apple. On macOS, the cask clears the quarantine flag from the binary during install, so Gatekeeper doesn't block it.
