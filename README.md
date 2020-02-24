# IPFS Desktop

> A desktop client for [IPFS](https://ipfs.io).
>
> You don't need the command line to run an IPFS node. Just install IPFS Desktop and have all the power of IPFS in your hands. Powered by [Web UI](https://github.com/ipfs-shipyard/ipfs-webui).

**Download the latest release**

- Mac - [IPFS-Desktop-0.10.3.dmg](https://github.com/ipfs-shipyard/ipfs-desktop/releases/download/v0.10.3/IPFS-Desktop-0.10.3.dmg) or `brew cask install ipfs`
- Windows - [IPFS-Desktop-Setup-0.10.3.exe](https://github.com/ipfs-shipyard/ipfs-desktop/releases/download/v0.10.3/IPFS-Desktop-Setup-0.10.3.exe) or `choco install ipfs-desktop`
- Linux - see the [install](#install) section for available options

![IPFS Desktop](https://user-images.githubusercontent.com/157609/55424318-426b1680-5580-11e9-93ec-ec261879367f.jpg)

[![](https://img.shields.io/badge/made%20by-Protocol%20Labs-blue.svg?style=flat-square)](https://protocol.ai/)
[![](https://img.shields.io/badge/project-IPFS-blue.svg?style=flat-square)](http://ipfs.io/)
[![](https://img.shields.io/badge/freenode-%23ipfs-blue.svg?style=flat-square)](http://webchat.freenode.net/?channels=%23ipfs)
[![](https://david-dm.org/ipfs-shipyard/ipfs-desktop.svg?style=flat-square)](https://david-dm.org/ipfs-shipyard/ipfs-desktop)
[![total download count](https://img.shields.io/github/downloads/ipfs-shipyard/ipfs-desktop/total.svg?style=flat-square)](https://github.com/ipfs-shipyard/ipfs-desktop/releases)
[![latest release download count](https://img.shields.io/github/downloads-pre/ipfs-shipyard/ipfs-desktop/v0.10.3/total.svg?style=flat-square)](https://github.com/ipfs-shipyard/ipfs-desktop/releases/tag/v0.10.3)

IPFS Desktop allows you to run your IPFS Node on your machine without having to bother with command line tools. With it, you have the power of [Web UI](https://github.com/ipfs-shipyard/ipfs-webui) on tip of your hands plus a handful of shortcuts you can find on settings.

> ⚠ Please note that this version is not stable yet and might change. Also, Linux support is still experimental and it might not work on every desktop environment. Please [file an issue](https://github.com/ipfs-shipyard/ipfs-desktop/issues/new) if you find a bug.

## Table of Contents

- [Features](#features)
- [Install](#install)
- [Contribute](#contribute)
    - [Translations](#translations)
- [FAQ](#faq)

## Features

### IPFS daemon always running

IPFS Desktop's main feature is to allow you to have the IPFS daemon always running in the background. But fear not! If you need to stop it, you can do it just by clicking on 'Stop'.

### Handle `ipfs://`, `ipns://` and `dweb:` links

If you come across a link to any of the protocols above, IPFS Desktop will be able to open them and redirect them to your default browser.

### Adds `ipfs` to your system

If you're using macOS or Windows and don't have `ipfs` installed on your system, IPFS Desktop will automatically install it so it is available through the command line. If you're using Linux, or already have `ipfs` installed, you can tell IPFS Desktop to take care of it (and keep it up to date!) by toggling the option on Settings.

### Easy add to IPFS

You can easily add files and folders to IPFS:

- On Windows, you can right click on files to add them to IPFS through IPFS Desktop.
- On macOS, you can drag and drop them to the tray icon.

### Download copied hashes

You can enable, on Settings, a shortcut to download an hash on the keyboard.

### Auto-add screenshots

You can enable, on Settings, a shortcut to take screenshots and add them automatically to IPFS.

## Install

Download the latest release of IPFS Desktop for your OS, below.

| Platform | Download link | Download count
|---------:|---------------|---------------
| **Windows**  | [IPFS-Desktop-Setup-0.10.3.exe](https://github.com/ipfs-shipyard/ipfs-desktop/releases/download/v0.10.3/IPFS-Desktop-Setup-0.10.3.exe) | [![](https://img.shields.io/github/downloads-pre/ipfs-shipyard/ipfs-desktop/v0.10.3/IPFS-Desktop-Setup-0.10.3.exe.svg?style=flat-square)](https://github.com/ipfs-shipyard/ipfs-desktop/releases/download/v0.10.3/IPFS-Desktop-Setup-0.10.3.exe)
| **Mac**    | [IPFS-Desktop-0.10.3.dmg](https://github.com/ipfs-shipyard/ipfs-desktop/releases/download/v0.10.3/IPFS-Desktop-0.10.3.dmg) | [![](https://img.shields.io/github/downloads-pre/ipfs-shipyard/ipfs-desktop/v0.10.3/IPFS-Desktop-0.10.3.dmg.svg?style=flat-square)](https://github.com/ipfs-shipyard/ipfs-desktop/releases/download/v0.10.3/IPFS-Desktop-0.10.3.dmg)

We provide multiple _experimental_ installers for **Linux** and **FreeBSD**:

| Package | Download link | Download count
|---------:|---------------|---------------
| tar | [ipfs-desktop-0.10.3-linux-x64.tar.xz](https://github.com/ipfs-shipyard/ipfs-desktop/releases/download/v0.10.3/ipfs-desktop-0.10.3-linux-x64.tar.xz) | [![](https://img.shields.io/github/downloads-pre/ipfs-shipyard/ipfs-desktop/v0.10.3/ipfs-desktop-0.10.3-linux-x64.tar.xz.svg?style=flat-square)](https://github.com/ipfs-shipyard/ipfs-desktop/releases/download/v0.10.3/ipfs-desktop-0.10.3-linux-x64.tar.xz)
| deb | [ipfs-desktop-0.10.3-linux-amd64.deb](https://github.com/ipfs-shipyard/ipfs-desktop/releases/download/v0.10.3/ipfs-desktop-0.10.3-linux-amd64.deb) | [![](https://img.shields.io/github/downloads-pre/ipfs-shipyard/ipfs-desktop/v0.10.3/ipfs-desktop-0.10.3-linux-amd64.deb.svg?style=flat-square)](https://github.com/ipfs-shipyard/ipfs-desktop/releases/download/v0.10.3/ipfs-desktop-0.10.3-linux-amd64.deb)
| rpm | [ipfs-desktop-0.10.3-linux-x86_64.rpm](https://github.com/ipfs-shipyard/ipfs-desktop/releases/download/v0.10.3/ipfs-desktop-0.10.3-linux-x86_64.rpm) | [![](https://img.shields.io/github/downloads-pre/ipfs-shipyard/ipfs-desktop/v0.10.3/ipfs-desktop-0.10.3-linux-x86_64.rpm.svg?style=flat-square)](https://github.com/ipfs-shipyard/ipfs-desktop/releases/download/v0.10.3/ipfs-desktop-0.10.3-linux-x86_64.rpm)
| AppImage | [ipfs-desktop-0.10.3-linux-x86_64.AppImage](https://github.com/ipfs-shipyard/ipfs-desktop/releases/download/v0.10.3/ipfs-desktop-0.10.3-linux-x86_64.AppImage) | [![](https://img.shields.io/github/downloads-pre/ipfs-shipyard/ipfs-desktop/v0.10.3/ipfs-desktop-0.10.3-linux-x86_64.AppImage.svg?style=flat-square)](https://github.com/ipfs-shipyard/ipfs-desktop/releases/download/v0.10.3/ipfs-desktop-0.10.3-linux-x86_64.AppImage)
| freebsd | [ipfs-desktop-0.10.3-linux-x64.freebsd](https://github.com/ipfs-shipyard/ipfs-desktop/releases/download/v0.10.3/ipfs-desktop-0.10.3-linux-x64.freebsd) | [![](https://img.shields.io/github/downloads-pre/ipfs-shipyard/ipfs-desktop/v0.10.3/ipfs-desktop-0.10.3-linux-x64.freebsd.svg?style=flat-square)](https://github.com/ipfs-shipyard/ipfs-desktop/releases/download/v0.10.3/ipfs-desktop-0.10.3-linux-x64.freebsd)

Or you can use your favorite package manager:

- **Homebrew** - `brew cask install ipfs`
- **Chocolatey** - `choco install ipfs-desktop`
- **Snap** - `snap install ipfs-desktop`
- **AUR** - [`ipfs-desktop` package](https://aur.archlinux.org/packages/ipfs-desktop/) maintained by [@alexhenrie](https://github.com/alexhenrie)

> Using package managers? Please head to [our package managers page](https://github.com/ipfs-shipyard/ipfs-desktop/issues/691) and help us add support for yours!

You can find releases notes and older versions on the [releases](https://github.com/ipfs-shipyard/ipfs-desktop/releases) page.

### Install from Source

To install it from source you need [Node.js](https://nodejs.org/en/) `>=10.4.0` and
need [npm](npmjs.org) `>=6.1.0` installed. This uses [`node-gyp`](https://github.com/nodejs/node-gyp) so **you must take a look** at their [platform specific dependencies](https://github.com/nodejs/node-gyp#installation).

Then the follow the steps below to clone the source code, install the dependencies and run it the app:

```bash
git clone https://github.com/ipfs-shipyard/ipfs-desktop.git
cd ipfs-desktop
npm ci
npm start
```

The IPFS Desktop app will launch and should appear in your OS menu bar.

## Translations

The translations are stored on [./assets/locales](./assets/locales) and the English version is the source of truth.
Other languages are periodically pulled from [Transifex](https://www.transifex.com/ipfs/ipfs-desktop/), a web interface to help us translate IPFS Desktop and its components to another languages.

## Releasing

- (Optional) Create a new [Draft Release](https://github.com/ipfs-shipyard/ipfs-desktop/releases).
- Bump the version in `package.json`
- Create a tag with the same version: `git tag vA.B.C`
- Publish local changes and the tag to GitHub repo: `git push && git push origin vA.B.C`
- Wait for the CI to upload the binaries to the draft release (a new one will be created if you haven't drafted one).
- The `latest.yml, latest-mac.yml, latest-linux.yml` files on the release are used by the app to determine when an app update is available. Once a release is published, users should recieve the app update. See: https://www.electron.build/auto-update.
- Update [Homebrew Cask](https://github.com/Homebrew/homebrew-cask/blob/master/CONTRIBUTING.md#updating-a-cask).
- Update Chocolatey package:
    1. Wait for the artefact on the [releases page](https://github.com/ipfs-shipyard/ipfs-desktop/releases)
    2. Run `node pkgs/chocolatey/update.js $version` - this script will update a few files:
        1. Update the version number on [ipfs-desktop.nuspec](./pkgs/chocolatey/ipfs-desktop.nuspec#L5)
        2. Update the binary URL on [chocolateyinstall.ps1](./pkgs/chocolatey/tools/chocolateyinstall.ps1#L3)
        3. Update the SHA256 of the binary on [chocolateyinstall.ps1](./pkgs/chocolatey/tools/chocolateyinstall.ps1#L4)
    3. Git commit with `pubchoco` in the commit message. Then CI should:
        1. `cd pkgs/chocolatey`
        2. `choco pack` - generates a `.nupkg` file.
        3. `choco push $generated_nupkg --key $api --source https://push.chocolatey.org`
- To start work on the next version, bump the version in the package.json and repeat theses steps.

## Contribute

[![](https://cdn.rawgit.com/jbenet/contribute-ipfs-gif/master/img/contribute.gif)](https://github.com/ipfs/community/#contributing-guidelines)

Feel free to join in. All welcome. Open an [issue](https://github.com/ipfs-shipyard/ipfs-desktop/issues)!

If you're interested in contributing translations, go to [project page on Transifex](https://www.transifex.com/ipfs/ipfs-desktop/translate/), create an account, pick a language and start translating.

This repository falls under the IPFS [Code of Conduct](https://github.com/ipfs/community/blob/master/code-of-conduct.md).

## FAQ

### Where is the configuration and logs?

The configuration file and logs are located on:
- Mac: `~/Library/Application Support/IPFS Desktop/`
- Windows: `%appdata%/IPFS Desktop/`
- Linux: `~/.config/IPFS Desktop/`

For quick access to this folders, just right-click on your tray icon and then 'Logs Directory' or 'Configuration File', depending on what you want.

**Note for developers:** When running dev version via `npm start` configuration will be placed in `/Electron/` instead of `/IPFS Desktop/` (`~/.config/Electron/config.json` on Linux). This is a known limitation of dev mode, does not impact packaged versions.

### How do we select the IPFS repo location?

We use [ipfsd-ctl](https://github.com/ipfs/js-ipfsd-ctl), which, in default conditions, will check `IPFS_PATH` environment variable. If not set, we fallback to `$HOME/.ipfs`. As soon as the first run has succeded, we save the information about the repository location in the configuration file, which becomes the source of truth.

### Which version of IPFS are we running?

Since we're using [ipfsd-ctl](https://github.com/ipfs/js-ipfsd-ctl), we have our own embedded IPFS binary. We try to always have the latest version.

### Which flags do we use to boot IPFS?

By default we use the flags `--migrate=true --routing=dhtclient ----enable-gc=true` when running the IPFS daemon. They can be changed via the configuration file, which can be easily accessed as mentioned above.

## License

[MIT Protocol Labs, Inc.](./LICENSE)
