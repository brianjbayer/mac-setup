# mac-setup
A basic collection of idempotent setup scripts for Mac-based
development.  Use these scripts instead of manually setting up
your basic Mac development environment.

---

## Recommended Use
Run the scripts from a local clone of this repository.

### Getting Started (Prerequisites)
1. `git clone` this repository, use `https:` for initial
   setup with no SSH

2. Change directory into the cloned repository
   ```bash
   cd mac-setup
   ```

### Configure Your Git Globals
To configure your git globals using the
`10-mac-config-git-globals` script, run command...
```
./10-mac-config-git-globals
```

### Add an SSH Key
To add an SSH key using the
`20-mac-add-new-ssh-key` script, run command...
```
./20-mac-add-new-ssh-key
```

---

### Installing Developer Tools and Applications

> :beer: **These scripts require [Homebrew](https://brew.sh/) package manager**

#### Homebrew Install `git` and `vim`
To Homebrew install `git` and `vim` with the
[Janus:Vim Distribution](https://github.com/carlhuda/janus) using the
`mac-install-git-vim-janus` script, run command...
```
./mac-install-git-vim-janus
```

#### Homebrew Install Apps (Chrome, Firefox, Docker, VS Code)
To Homebrew install your applications like Chrome, Firefox,
Docker Desktop, and Visual Studio (VS) Code using the
`mac-install-dev-apps` script, run command...
```
./mac-install-dev-apps
```

:sparkles: Use the `-a` option to **override** and specify
your own applications to install
```
./mac-install-dev-apps -a "docker visual-studio-code"
```

#### Homebrew Install `rbenv`
To Homebrew install `rbenv` and add its initialization
to your `.zshrc` file using the
`mac-install-rbenv` script, run command...
```
./mac-install-rbenv
```
