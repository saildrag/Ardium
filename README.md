<p align="center"><img src="./app/assets/images/SealCircle.png" width="150px" height="150px" alt="aventium softworks"></p>

<h1 align="center">Ardium Launcher</h1>

<em><h5 align="center">(formerly Electron Launcher)</h5></em>

<p align="center">Permet de rejoindre le serveur Ardium !</p>

## Downloads

You can download from [GitHub Releases](https://github.com/saildrag/Ardium/releases)

#### Latest Release

[![](https://img.shields.io/github/release/saildrag/Ardium.svg?style=flat-square)](https://github.com/saildrag/Ardium/releases/latest)

#### Latest Pre-Release
[![](https://img.shields.io/github/release/saildrag/Ardium/all.svg?style=flat-square)](https://github.com/saildrag/Ardium/releases)

**Supported Platforms**

If you download from the [Releases](https://github.com/saildrag/Ardium/releases) tab, select the installer for your system.

| Platform | File |
| -------- | ---- |
| Windows x64 | `Ardium-Launcher-setup-VERSION.exe` |
| macOS x64 | `Ardium-Launcher-setup-VERSION.dmg` |
| macOS arm64 | `Ardium-Launcher-setup-VERSION-arm64.dmg` |
| Linux x64 | `Ardium-Launcher-setup-VERSION.AppImage` |

## Console

To open the console, use the following keybind.

```console
ctrl + shift + i
```

Ensure that you have the console tab selected. Do not paste anything into the console unless you are 100% sure of what it will do. Pasting the wrong thing can expose sensitive information.

#### Export Output to a File

If you want to export the console output, simply right click anywhere on the console and click **Save as..**

![console example](https://i.imgur.com/T5e73jP.png)


## Development

This section details the setup of a basic developmentment environment.

---

**Launch Application**

```console
> npm start
```

---

**Build Installers**

To build for your current platform.

```console
> npm run dist
```

Build for a specific platform.

| Platform    | Command              |
| ----------- | -------------------- |
| Windows x64 | `npm run dist:win`   |
| macOS       | `npm run dist:mac`   |
| Linux x64   | `npm run dist:linux` |

Builds for macOS may not work on Windows/Linux and vice-versa.

---