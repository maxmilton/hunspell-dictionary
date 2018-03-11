# Hunspell Dictionary For Developers

An custom dictionary for Hunspell with support for programming terms.

## Overview

Features:

* based on Australian English
* common programming language terms
* many custom words and manual clean up

## Usage

TODO: Write me!

### Use in VS Code (on Linux)

```shell
#ln -s <PathToThisDirectory> ~/.config/Code/Dictionaries
ln -s ./ ~/.config/Code/Dictionaries
```

then install the `Spell Right` extension. Also see the [Spell Right docs](https://github.com/bartosz-antosik/vscode-spellright).

## TODO

* Find original sources and attribute properly. They probably have various licences which should be respected.
  * base source package is from Chromium
  * programming terms from:
    * <https://github.com/Jason-Rev/vscode-spell-checker> (original inspiration for this!)
    * <https://github.com/Jason3S/cspell-dicts>
    * <https://github.com/Jason3S/cspell>
* Split the dictionary into separate files based on original source + my custom lists.
* Create a script to combine the source dictionaries into a single `.dic` file + automatically remove any duplicates and comments.
* Make an easy way to download (and keep up to date?) the latest dictionary + write usage instructions in readme.

## Licence

This is an MIT licensed open source project. See [LICENCE](https://github.com/MaxMilton/hunspell-dictionary/blob/master/LICENCE).

-----

© 2018 [Max Milton](https://maxmilton.com)
