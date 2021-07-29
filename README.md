# N. Kostin's Artix Linux Bootstrapping Scripts (inspired by LARBS)

## Installation:

Run the following commands as a root user:

```
curl -LO https://raw.githubusercontent.com/nkostin4/deploy-artix/master/stable.sh
sh stable.sh
```

Alternatively, for the testing (unstable) version, run

```
curl -LO https://raw.githubusercontent.com/nkostin4/deploy-artix/master/testing.sh
sh testing.sh
```

## What does this script do?

This is a bootstrapping script that is meant to be run after installing Artix Linux (ideally witht the OpenRC init system). Specifically, it

- Installs the programs in the `progs.csv` file.
- Deploys [my dotfiles](https://github.com/nkostin4/circles).

After running this script, enjoy a comfy (and highly productive) desktop.
