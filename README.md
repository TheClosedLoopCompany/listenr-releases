# Listenr releases

Public release artifacts for [Listenr](https://listenr.live) — bot-free
meeting notes for macOS with real speaker attribution.

## Install

- **Download**: grab `Listenr.dmg` from the
  [latest release](https://github.com/TheClosedLoopCompany/listenr-releases/releases/latest),
  open it, drag Listenr to Applications.
- **Homebrew**: `brew install --cask theclosedloopcompany/tap/listenr`
- **Terminal**: `curl -fsSL https://listenr.live/install.sh | sh`

Requires macOS 15 (Sequoia) or later. All builds are Developer ID-signed and
notarized by Apple. The app updates itself via
[Sparkle](https://sparkle-project.org) (`appcast.xml` in this repo is the
update feed).

## What's in a release

| Asset | Purpose |
| --- | --- |
| `Listenr-x.y.z.dmg` | Drag-and-drop installer |
| `Listenr-x.y.z.zip` | App bundle (Homebrew, Sparkle, install.sh) |
| `Listenr.dmg` / `Listenr.zip` | Stable-named copies for `releases/latest/download/…` links |
