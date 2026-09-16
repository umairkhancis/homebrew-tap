# umairkhancis/homebrew-tap

Homebrew formulae for [Inshirah](https://github.com/umairkhancis/inshirah) — a
thoughtful surface over Claude Code.

```sh
brew install umairkhancis/tap/inshirah
```

Then, if you have never signed into Claude Code on this machine:

```sh
inshirah --login      # sign in, then /exit to come back
```

The formula is generated from PyPI and pinned to wheels. The download is a few
hundred megabytes because `claude-agent-sdk` bundles the Claude Code binary.

The canonical copy of the formula lives in the main repo at
`deploy/homebrew/inshirah.rb`, versioned next to the code it installs; this tap
is where Homebrew reads it from. See `docs/homebrew.md` there for the release
checklist.
