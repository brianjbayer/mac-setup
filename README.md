# mac-setup
A basic collection of idempotent setup scripts for
Mac-based development

## Recommended Use
Run the scripts from a local clone of this repository

1. Git clone this repository, use `https:` for initial
   setup with no SSH

2. Change directory into the cloned repository
   ```bash
   cd mac-setup
   ```

3. Configure your git global settings by running
   ```
   ./10-mac-config-git-globals
   ```

4. Add an SSH key by running
   ```
   ./20-mac-add-new-ssh-key
   ```

### Installing Developer Tools and Applications

#### Homebrew Install `git` and `vim`
Homebrew install `git` and `vim` with the
[Janus:Vim Distribution](https://github.com/carlhuda/janus)

```
./mac-install-git-vim-janus
```

#### Homebrew Install Apps (Chrome, Firefox, Docker, VS Code)
Homebrew install `git` and `vim` with the
[Janus:Vim Distribution](https://github.com/carlhuda/janus)

```
./mac-install-dev-apps
```

:sparkles: Use the `-a` option to **override** and specify
your own applications to install
```
./mac-install-dev-apps -a "docker visual-studio-code"
```
