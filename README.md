# Jesus's dotfiles

![](https://cloud.githubusercontent.com/assets/3719969/14582971/23fa4a0e-040c-11e6-93d2-1ce8d9d1951c.png)

## Setup

### Installation
- Fork & clone the repo 🔀
- Add your `.gitconfig.local` file (see [private config](#private-config)) ⚙
- Read and run `symlink-setup.sh` ⚡️
- Read and run parts of `setup-a-new-machine.sh` 💻
- Enjoy! 👌

### Add new dotfiles
Just `cd` to your `dotfiles` repository, add your new dotfiles and then run `symlink-setup.sh`

## Summary of files

### Automatic config
* `.vimrc`
* `.inputrc`
* `.hyper.js`

### Shell
* `.aliases`
* `.bash_profile`
* `.bash_prompt`
* `.bashrc`
* `.zshrc`
* `.exports`
* `.functions`
* `.path`

### Editor
* `.editorconfig` - More info at [editorconfig.org](http://editorconfig.org/).

### Git
* `.gitconfig`
* `.gitignore`

### Commands (~/bin)
* Binaries that aren't via an npm/npx or homebrew.

### Manual run
* `symlink-setup.sh`
* `setup-a-new-machine.sh`
  * `brew.sh`, `npm.sh`, `vscode.sh`, `macos.sh`

## Private config

### Git
Use `~/.gitconfig.local` for your private git configuration. Eg: username, tokens...

```bash
[user]
  name = John Doe
  email = johndoe@example.com
# ...
```

### Extra
You can create a file `~/.extra` and add your private configuration.

My `~/.extra` looks something like this:
```bash
# Project aliases
alias dotfiles="cd ~/Dev/projects/dotfiles"
# ...
```
Also you can use this file for override settings, functions and aliases.

## Thanks to...
This project is principally for personal use and is based on Mathias' and Paul's dotfiles.

## License
MIT © [marioblas](https://github.com/marioblas)
