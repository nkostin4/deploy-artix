# N. Kostin's Artix Linux Bootstrapping Scripts (inspired by [LARBS](https://larbs.xyz/))

## Installation

Run the following as a root user:

```
curl -LO https://raw.githubusercontent.com/nkostin4/deploy-artix/master/stable.sh
sh stable.sh
```

## What does this script do?

This bootstrapping script is intended to be run after installing Artix Linux (with the OpenRC init system). Specifically, it

- installs the programs in the `progs.csv` file, and
- deploys [my dotfiles](https://github.com/nkostin4/circles).

After running this script, enjoy a productive desktop.
