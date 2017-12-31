# Glyphr Studio Desktop

Desktop application for [Glyphr Studio](http://glyphrstudio.com) built in [Electron](https://electron.atom.io/)!

## Download

- [Mac 64-bit](https://github.com/glyphr-studio/Glyphr-Studio-Desktop/releases/download/v0.4.1/Glyphr.Studio-darwin-x64.zip)
- [Windows 64-bit](https://github.com/glyphr-studio/Glyphr-Studio-Desktop/releases/download/v0.4.1/Glyphr.Studio-win32-x64.zip)
- [Windows 32-bit](https://github.com/glyphr-studio/Glyphr-Studio-Desktop/releases/download/v0.4.1/Glyphr.Studio-win32-ia32.zip)
- [Linux 64-bit](https://github.com/glyphr-studio/Glyphr-Studio-Desktop/releases/download/v0.4.1/Glyphr.Studio-linux-x64.zip)
- [Linux 32-bit](https://github.com/glyphr-studio/Glyphr-Studio-Desktop/releases/download/v0.4.1/Glyphr.Studio-linux-ia32.zip)

## How to run from source

Be sure to have [Node.js](https://nodejs.org) and [git](https://git-scm.com) installed.

Then:

```
git clone https://github.com/glyphr-studio/Glyphr-Studio-Desktop.git
cd Glyphr-Studio-Desktop
npm i
node build.js // needed after each npm i
electron .
```

## Build

Builds are constructed with [electron-packager](https://github.com/maxogden/electron-packager).

Be sure to have [Node.js](https://nodejs.org) and [git](https://git-scm.com) installed.

First, be sure to run:

```
git clone https://github.com/glyphr-studio/Glyphr-Studio-Desktop.git
cd Glyphr-Studio-Desktop
npm i
node build.js // needed after each npm i
```

Then:

All Platforms: `node packager.js`

64-Bit Platforms Only: `node packager.js -64`

macOS: `node packager.js -mac`

Windows 64-Bit: `node packager.js -win`

Windows 32-Bit: `node packager.js -win32`

Linux 64-Bit: `node packager.js -linux`

Linux 32-Bit: `node packager.js -linux32`

## Troubleshooting

Ubuntu users may need to `sudo apt install libgconf-2-4` in order to run the app.