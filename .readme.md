# macOS Application Config Files

This repository contains configuration files for various macOS applications. It is intended to help you manage, back up, and restore your app settings easily.

## Usage
Clone this repository so that all files are stored in your `~/.config` directory:

```sh
git clone git@github.com:addei/macos-configs.git /Users/$USER/.config
```

## Apps

List of apps and overrides that needs to be set before configurations are in use.

### btop

Works out of the box.

### fastfetch

Works out of the box.

### iterm2

Note! To enable iterm2 configuration file, Enable “Load preferences from a custom folder or URL.” and add path ```/Users/$USER/.config/iterm2```.

## Removing the Repository and Git
To remove the repository and all its files, including the `.git` directory:

```sh
rm -rf /Users/$USER/.config
```

This will delete the entire `.config` folder and all its contents. Use with caution!

Alternatively, if you only want to remove git tracking but keep the config files:

```sh
rm -rf /Users/$USER/.config/.git
```

This will remove the `.git` directory and stop git tracking, but leave your config files intact.
