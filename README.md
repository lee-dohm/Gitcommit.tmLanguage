# Git Commit Syntax Definition

A Sublime Text 2 syntax definition file to offer syntax coloring for when you use Sublime Text as your editor for your Git commit messages.  *It may work with TextMate also, but I haven't tested it.*

# Installation

## Manual Installation

Go to the "Packages" directory (`Preferences` / `Browse Packages...`).  Then clone this repository:

    git clone git://github.com/lee-dohm/Gitcommit.tmLanguage

# Usage

Once installed, if you have configured Sublime Text to be your editor for your Git commit messages you should notice the following:

## Complete
* Lines beginning with `#` should look like comments.

## Planned 

* The first line should be colored as a string until you pass the 50<sup>th</sup> column, then it should be colored like an error.
* The second line should be colored like an error if there is any text in it.
* Successive lines should be colored like strings.

# Information

Source: https://github.com/lee-dohm/Gitcommit.tmLanguage

Authors: [Lee Dohm](https://github.com/lee-dohm), [Lifted Studios](https://github.com/lifted-studios)