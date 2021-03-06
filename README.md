[![report](https://goreportcard.com/badge/github.com/ahmadkabdullah/winela)](https://goreportcard.com/report/github.com/ahmadkabdullah/winela)
[![release](https://img.shields.io/github/v/release/ahmadkabdullah/winela?include_prereleases&label=Release&color=blue)](https://github.com/ahmadkabdullah/winela/releases)
[![license](https://img.shields.io/github/license/ahmadkabdullah/winela?label=License&style=flat&color=red)](https://github.com/ahmadkabdullah/winela/blob/main/LICENSE)


Winela is a commandline launcher for executables through winehq. It is meant to help with finding and executing exe files without installing bloated programs that typically limit you to installing from things.

## Usage
Winela operates on two files stored in specific dir in the config dir (usually **~/.config/winela/**):
- **wineladb**: storing list of exes to launch
- **winelarc**: containing configuration for specifying wine version and parameters.

You can *scan* to populate **wineladb** with exe files in a directory (on first run, this also creates the other file).

You can *list* the exe files acquired from the scan. This reads out a numerated version of **wineladb**.

You can *run* an item from the (numerated) list. Also can choose to fork the process or not.
