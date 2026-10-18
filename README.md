# homebrew-signalladder

The Homebrew tap for [SignalLadder](https://github.com/JWhite212/SignalLadder), a macOS menu-bar app that sounds, or speaks, only for the notifications your rules pick out.

## Install

```sh
brew install --cask jwhite212/signalladder/signalladder
```

It installs the same signed, notarised disk image as the [GitHub release](https://github.com/JWhite212/SignalLadder/releases/latest). SignalLadder needs macOS 14 (Sonoma) or later on an Apple silicon Mac. On first launch, follow its Setup Guide to grant Accessibility.

## Update

SignalLadder never checks for updates itself and makes no network connection. To update:

```sh
brew update
brew upgrade --cask signalladder
```

## Uninstall

```sh
brew uninstall --cask signalladder
```

This quits SignalLadder first. To also remove your rules, sounds and settings, add `--zap`.

## Where the cask comes from

The cask is kept in the SignalLadder repository, at [`Packaging/homebrew/Casks/signalladder.rb`](https://github.com/JWhite212/SignalLadder/blob/main/Packaging/homebrew/Casks/signalladder.rb), and copied here with each release. Report problems in [SignalLadder's issues](https://github.com/JWhite212/SignalLadder/issues).
