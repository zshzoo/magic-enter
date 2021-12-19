# magic-enter

[![License](https://img.shields.io/badge/license-MIT-007EC7)](/LICENSE)
[![built for](https://img.shields.io/badge/built%20for-%20%F0%9F%A6%93%20zshzoo-black)][zshzoo]
[![works with prezto](https://img.shields.io/badge/works%20with-%E2%9D%AF%E2%9D%AF%E2%9D%AF%20prezto-red)](#install-for-prezto)

> Make your enter key magical by binding a Zsh command to it

## Description

Based on [magic-enter](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/magic-enter).

## Installation

### Install with a Zsh plugin manager

To install using a Zsh plugin manager, add the following to your .zshrc

- [pz]: `pz source zshzoo/magic-enter`
- [zcomet]: `zcomet load zshzoo/magic-enter`
- [zgenom]: `zgenom load zshzoo/magic-enter`
- [znap]: `znap source zshzoo/magic-enter`

### Install manually, without a plugin manager

To install manually, first clone the repo:

```zsh
git clone https://github.com/zshzoo/magic-enter ${ZDOTDIR:-~}/.zplugins/magic-enter
```

Then, in your .zshrc, add the following line:

```zsh
source ${ZDOTDIR:-~}/.zplugins/magic-enter/magic-enter.zsh
```

### Install for Prezto

To install with [Prezto][prezto], first clone the repo from an interactive Zsh session:

```zsh
# make sure your $ZPREZTODIR is set
ZPREZTODIR=${ZPREZTODIR:-~/.zprezto}
# clone the repo to a prezto contrib dir
git clone https://github.com/zshzoo/magic-enter $ZPREZTODIR/contrib/magic-enter/external
# set up the contrib
echo "source \${0:A:h}/external/magic-enter.plugin.zsh" > $ZPREZTODIR/contrib/magic-enter/init.zsh
```

Then, add the plugin to your Prezto plugins list in .zpreztorc

```zsh
zstyle ':prezto:load' pmodule \
  ... \
  magic-enter \
  ...
```

[ohmyzsh]: https://github.com/ohmyzsh/ohmyzsh
[prezto]: https://github.com/sorin-ionescu/prezto
[zshzoo]: https://github.com/zshzoo/zshzoo
[pz]: https://github.com/mattmc3/pz
[zcomet]: https://github.com/agkozak/zcomet
[zgenom]: https://github.com/jandamm/zgenom
[znap]: https://github.com/marlonrichert/zsh-snap
