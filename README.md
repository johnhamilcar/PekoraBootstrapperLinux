# Pekora Player Bootstrapper for Linux

This is an **unofficial** bootstrapper for Pekora on Linux.
Tested on:
CachyOS

Prerequisites:
Wine
Winetricks

Uses Wine and DXVK to provide a performant experience on 2018, 2020, and 2021 clients. 
2017 does **not** work due to 2017 anticheat only working on Windows.

Written in Rust.

## Usage
To install it, simply run it in your terminal, like so: ./PekoraPlayerBootstraapper
It might be necessary to give it permission to run, using chmod +x [file]

To launch a game, simply go onto the website and click the Play button. 2017 games will NOT work.

To uninstall, run the bootstrapper with the ``-u`` argument. A desktop shortcut should've also been made called "Uninstall Pekora Player", if you'd prefer that.

Install locations:
~/.local/share/Pekora
~/.wine-pekora
