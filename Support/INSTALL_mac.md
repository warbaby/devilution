# Installation

## Dependencies

[Homebrew](https://brew.sh/)

```bash
brew install wine
brew install mingw-w64
ln -s /usr/local/Cellar/mingw-w64/5.0.4/toolchain-x86_64/bin/x86_64-w64-mingw32-windres /usr/local/bin/windres
```

## Building

```bash
git clone https://github.com/galaxyhaxz/devilution
cd devilution
cp /path/to/diablo_game_dir/diabloui.dll .
cp /path/to/diablo_game_dir/Storm.dll .
make
```

## Install

```bash
cp devilution.exe /path/to/diablo_game_dir/
```

## Run

```bash
wine devilution.exe
```
