# Dotfiles

Various dotfiles for customization.

## Prereqs

Make sure to install the following on the new system.

### Get git
```
sudo dnf install git
```
```
sudo pacman -S git
```

### Get GNU Stow
```
sudo dnf install stow
```
```
sudo pacman -S stow
```

## Install it

```
git clone git@github.com/dkazha/dotfiles.git
cd dotfiles
```

## Create symlinks with GNU Stow

```
stow .
```
