# Ionic Package Manager

> For linux systems

## What is Ionic package manager?
firstly, a package manager is a way to install software either for a GUI
or a CLI

**Ionic Package manager** is just another package manager, but includes *more* features
## Ionic Dependency Manager
Manage Dependencies with `idm` (ionic dependency manager)
## Syntax

### in (package manager)
So to install:
```bash
in install [options] <package>
```
and to upgrade/update
```bash
in update
in upgrade
```
also see:
```bash
in --upload
```
to upload a custom package of your `own`
### idm (dependency manager)
To install
```bash
idm install [options] <package>
```
globaly:
```bash
idm install -g [options] <package>
```
to upgrade/update
```bash
idm -u
# or
idm upgrade
```
> Note: update and upgrade are the same command, to use on seperatly use the `--upgrade` and `--update` flags
> Nte: installs do not currently work, unfortunately

## Install
to install on linux:
Arch: `sudo pacman -S ionic-package-manager`
Debian: `sudo apt install ionic-package-manager`
fedora: `sudo dnf install ionic-package-manager`

> Sorry, but in is only currently supported for linux

## inc
### what is the inc.js frame work
it is a Meta Frame work (like `next.js`) which includes a frontend
and an api to interact with *most* backends
> Note: the server is not included, you will need to get your own database and server

### how to get started
run this after installing:
```bash
idm init inc-app my-inc-app
```
and run through the **prompts**
after you finish, get started by editing src/main.js (or main.ts)
