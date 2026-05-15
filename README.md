# homebrew-mq-dir

Homebrew tap for [**mq-dir**](https://github.com/h5nam/mq-dir) — a quad-pane native macOS file manager.

## Install

```sh
brew install --cask h5nam/mq-dir/mq-dir
```

`brew` tap-installs the formula on first use; no separate `brew tap` step is required.

## Update

```sh
brew upgrade --cask mq-dir
```

The cask points at the signed + notarized DMG published in the [mq-dir releases](https://github.com/h5nam/mq-dir/releases). New releases land here automatically (CI in the main repo pushes a refreshed `Casks/mq-dir.rb` whenever `Scripts/release.sh` cuts a tag).

## Uninstall

```sh
brew uninstall --cask mq-dir
```

`brew uninstall --zap --cask mq-dir` also wipes the app's persisted state under `~/Library/Application Support/com.mqdir.app` and friends.

## Project

Bug reports, contributions, and source live in the main repository: <https://github.com/h5nam/mq-dir>.
