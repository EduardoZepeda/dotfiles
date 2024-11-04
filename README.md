# My chezmoi configuration files

This is a personal repo to host my dotfiles. Check chezmoi for more information please check [Chezmoi's official page](https://www.chezmoi.io/)

## Quickstart

On a new fresh Linux installation (Debian should work) run the following command. Replacing *$GITHUB_USERNAME* for your desired Github username:

``` bash
sh -c "$(curl -fsLS get.chezmoi.io)" -- init --apply $GITHUB_USERNAME
```

Alternatively, if you already installed chezmoi, you can just run

``` bash
chezmoi update
```

This should install all packages without all the hassle of doing it manually. 

## Packages installed

| Installed               | Description                                         |
| ----------------------- | --------------------------------------------------- |
| Bun                     | Ultra fast javascript runtime                       |
| Codium                  | Free/Libre Open Source Software Binaries of VS Code |
| Docker                  | Default software containers                         |
| Go                      | The ultimate get shit done language, fast enough    |
| Kubernetes              | Container orchestration                             |
| Nerdfonts               | Lots of fonts                                       |
| Noisetorch              | Noise reduction for your microphone                 |
| NVM                     | Node version manager                                |
| Multiple packages       | Random stuff                                        |
| Pip (And some packages) | Python package manager                              |
| Rust                    | Some serious programming language                   |
| Zsh                     | My favorite shell                                   |