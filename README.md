# Homebrew Tap for dimelords

Official Homebrew tap for dimelords projects.

## Installation

```bash
brew install dimelords/tap/huddle-mcp
brew install dimelords/tap/protoc-gen-utcp
```

Tapping first (`brew tap dimelords/tap`) also works, and then the names can be
used on their own.

## What is here

| | |
| --- | --- |
| **huddle-mcp** | The client for [huddle](https://github.com/dimelords/huddle): the hooks the Huddle pane runs in Claude Code, the channel bridge and image uploads. Shipped as a cask. |
| **protoc-gen-utcp** | A Protocol Buffer compiler plugin that generates [UTCP](https://github.com/dimelords/protoc-gen-utcp) definitions. Shipped as a formula. |

The casks and formulae here are written by GoReleaser when each project
releases, and the binaries they download come from that project's own release,
so Homebrew needs no credentials. Edit them in the project, not here.
