# Dot Edit
> [!TIP]
> If you are having issues, please tell me what the issue is in the [issues tab](https://github.com/TheKamboy/dotedit-bash/issues).

A very simple dot editor that I created.

## CHANGELOG
The changelog is stored in [changelog.adoc](./CHANGELOG.adoc).

## Requirements
There is only one lol.

### Fzf
> [!NOTE]
> This table was taken from the [fzf repository](https://github.com/junegunn/fzf/), for more info about fzf, go there.

| Package Manager | Linux Distribution      | Command                            |
| --------------- | ----------------------- | ---------------------------------- |
| APK             | Alpine Linux            | `sudo apk add fzf`                 |
| APT             | Debian 9+/Ubuntu 19.10+ | `sudo apt install fzf`             |
| Conda           |                         | `conda install -c conda-forge fzf` |
| DNF             | Fedora                  | `sudo dnf install fzf`             |
| Nix             | NixOS, etc.             | `nix-env -iA nixpkgs.fzf`          |
| Pacman          | Arch Linux              | `sudo pacman -S fzf`               |
| pkg             | FreeBSD                 | `pkg install fzf`                  |
| pkgin           | NetBSD                  | `pkgin install fzf`                |
| pkg_add         | OpenBSD                 | `pkg_add fzf`                      |
| Portage         | Gentoo                  | `emerge --ask app-shells/fzf`      |
| Spack           |                         | `spack install fzf`                |
| XBPS            | Void Linux              | `sudo xbps-install -S fzf`         |
| Zypper          | openSUSE                | `sudo zypper install fzf`          |

## Installation
> [!NOTE]
> If you can't run `dotedit` after the installation, you may need to add `~/.local/bin` to your `PATH`.

1. Clone the repository: `git clone https://github.com/TheKamboy/dotedit-bash.git`
1. Enter the repository: `cd dotedit-bash`
1. Copy `dotedit` to your local bin: `mkdir -p ~/.local/bin && cp dotedit ~/.local/bin/dotedit`


## Usage
Just run `dotedit`.

## Configuration
You can configure it with the variables in it.

``` bash
# VARIABLES
folders=""
usefoldersfromconfig=true
editor=$EDITOR
debug=false
# VARIABLES
```

- folders: add custom folders to the search
- usefoldersfromconfig: adds folders from your `.config` into the search
- editor: the editor you want to use
- debug: more verbose
