<p align="center">
  <a href="https://github.com/MarioCatuogno/Clean-macOS">
 <img width=200px src="https://raw.githubusercontent.com/MarioCatuogno/Clean-macOS/master/img/logo_clean_macos.png" alt="Clean-macOS logo"></a>
</p>

<h2 align="center">Clean mac-OS</h2>

<div align="center">

[![Status](https://img.shields.io/github/last-commit/MarioCatuogno/Clean-macOS.svg?style=flat-square)](https://github.com/MarioCatuogno/Clean-macOS/commits/master)
[![GitHub Issues](https://img.shields.io/github/issues/MarioCatuogno/Clean-macOS.svg?style=flat-square)](https://github.com/MarioCatuogno/Clean-macOS/issues)
[![License](https://img.shields.io/badge/license-MIT-orange.svg?style=flat-square)](https://github.com/MarioCatuogno/Clean-macOS/blob/master/LICENSE)
[![Version](https://img.shields.io/github/v/release/MarioCatuogno/Clean-macOS.svg?style=flat-square)](https://github.com/MarioCatuogno/Clean-macOS/releases)

</div>

---

<p align="center">
💻 A shell script to install and configure macOS.
  <br>
</p>

## Table of content

- [Table of content](#table-of-content)
- [About](#about)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installing](#installing)
- [Useful links](#useful-links)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)

## About

__Clean-macOS__ is a simple script which keeps updated the mac-OS or install all the stuff after a clean installation. It uses _dotfiles_ and _shell scripts_ in order to speed up the configuration of mac-OS when you have to re-install your computer.

I've seen various repositories of various people on Github, and every single one of them seemed to be very different. The reason for this is that _dotfiles_ are very personal and there is no "best setup". What I tried to acoomplish with this project is to create the simpliest setup for different kind of users: basic, developers, photographer, etc.

To do this I dove deep down into several repositories (see [Acknowledgements](#acknowledgements)) and found incredible ways to tweak various setup or organize things.

The basic idea behind this project is that the setup and configuration of a new Mac should be as smooth, simple and fast as possible. For this reason there is just one script that prompts a menu from which you chose what kind of profile you want to install on your Mac. Each profile has different apps/options but everyone shares a "core" function that install basic apps, dependencies or binaries. So no matter if you're a developer or a graphic designer, your Mac will be run just fine.

## Getting Started

You need an active internet connection and one of the following macOS version:

* macOS 10.12 "Sierra"
* macOS 10.13 "High Sierra"
* macOS 10.14 "Mojave"
* macOS 10.15 "Catalina"

## Prerequisites

1. Do a fresh install of macOS (version 10.12+)
2. Open __Terminal.app__ and download the project with the following command `git clone https://github.com/MarioCatuogno/Clean-macOS.git ~/cleanMacOS`
3. If you want to change the apps that will be installed edit the `Brewfile` file
4. Launch the command `chmod 777 ~/cleanMacOS/cleanMacOS.sh`

## Installing

Open __Terminal.app__ and run the following command `~/cleanMacOS/cleanMacOS.sh`, the following promtp will appear from which you can choose one of the options:

<p align="center">
  <a href="https://github.com/MarioCatuogno/Clean-macOS">
  <img width=600px src="https://raw.githubusercontent.com/MarioCatuogno/Clean-macOS/master/img/scrn_cleanmacos_terminal.png" alt="Clean-macOS terminal"><br></a>
</p>

1. `Install Homebrew`: install Homebrew package and dependencies
2. `Install Applications`: install binaries, cask and Mac Apple Store application listed in profile files
3. `Configure macOS`: configure macOS with useful commands
4. `Update`: update brews, casks and MAS applications and formulaes

If you have done a fresh install, run all the commands in the sequence listed above. For details on how to run the script click [__here__](https://github.com/MarioCatuogno/Clean-macOS/blob/master/doc/SETUP.md).

## Useful links

Click [__here__](https://github.com/MarioCatuogno/Clean-macOS/blob/master/doc/APPS_LIST.md) to find a collection of various apps I've personally tested or used in the past on macOS.

Click [__here__](https://github.com/MarioCatuogno/Clean-macOS/blob/master/doc/APPS_REMOVED.md) to find a list of all apps used in previous script versions.

## Roadmap

To check the current status and the upcoming milestones of the Clean-macOS project, click [__here__](https://github.com/MarioCatuogno/Clean-macOS/projects/8).

For the full changelog history, click [__here__](https://github.com/MarioCatuogno/Clean-macOS/blob/master/doc/CHANGELOG.md).

## Contributing

You are encouraged to fork this repository and to open issue to discuss the change you wish to make. If you want to actively contribute, click [__here__](https://github.com/MarioCatuogno/Clean-macOS/blob/master/doc/CONTRIBUTING.md) for guidelines.

If you find it useful, please star or tell others about this repo.

## Acknowledgements

+ [@mathiasbynens](https://github.com/mathiasbynens) for his amazing [dotfiles](https://github.com/mathiasbynens/dotfiles)
+ [@mikaelgustafsson](https://mikaelgustafsson.art) for his amazing [wallpapers](https://www.instagram.com/mklgustafsson/)
+ [@robbyrussell](https://github.com/robbyrussell) for the guides of [Oh My Zsh](https://github.com/robbyrussell/oh-my-zsh)

---

<p align="center">
  <a href="https://github.com/MarioCatuogno/Clean-macOS">
  <img width=600px src="https://raw.githubusercontent.com/MarioCatuogno/Clean-macOS/master/img/scrn_mydesktop.png" alt="Clean-macOS desktop"><br></a>
</p>
