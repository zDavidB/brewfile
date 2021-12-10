# brewfile
Homebrew brewfile to install the core set of apps for Macbook

Having installed the Homebrew app

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Download the `Brewfile` or clone this repo

## Import from Brewfile
Run the cmd from the same folder of Brewfile

```bash
brew bundle install
```
The `install` may need a few runs to clear all errors on the dependancies

## Dump current apps to Brewfile - refresh the file
in the git repo folder
```
brew bundle dump
```
## Check if all dependencies are installed from the Brewfile.

```bash
brew bundle check
```

## List all dependencies present in the Brewfile

```bash
brew bundle list
```
