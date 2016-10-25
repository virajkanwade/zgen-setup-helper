# zgen-setup-helper
[oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) like install script for [zgen](https://github.com/tarjoilija/zgen)

## Getting Started

### Prerequisites

* Unix-based operating system (macOS or Linux)
* [Zsh](http://www.zsh.org) should be installed (v4.3.9 or more recent). If not pre-installed (`zsh --version` to confirm), check the following instruction here: [Installing ZSH](https://github.com/robbyrussell/oh-my-zsh/wiki/Installing-ZSH)
* `curl` or `wget` should be installed
* `git` should be installed

### Basic Installation

zgen is installed by running one of the following commands in your terminal. You can install this via the command-line with either `curl` or `wget`.

#### via curl

```shell
sh -c "$(curl -fsSL https://raw.githubusercontent.com/virajkanwade/zgen-setup-helper/master/tools/install.sh)"
```

#### via wget

```shell
sh -c "$(wget https://raw.githubusercontent.com/virajkanwade/zgen-setup-helper/master/tools/install.sh -O -)"
```

## Next:
https://github.com/tarjoilija/zgen

## TODO:
* Auto-update
* Add information about compaudit/compinit warning. Something along the lines of https://github.com/robbyrussell/oh-my-zsh/blob/master/lib/compfix.zsh
