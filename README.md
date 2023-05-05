# .dotfiles
Dotfiles saving and syncing between all my devices (ultimate goal) using [chezmoi](https://www.chezmoi.io/).

## Installation
- chezmoi can be installed with:
``` bash
sh -c "$(curl -fsLS get.chezmoi.io)" -- init --apply $GITHUB_USERNAME
```

- It can be updated with:
``` bash
chezmoi update
```

## Documentation
- Homepage: [https://www.chezmoi.io](https://www.chezmoi.io)
- Quick Start: [https://www.chezmoi.io/quick-start/](https://www.chezmoi.io/quick-start/)
- [User Guide](https://www.chezmoi.io/user-guide/command-overview/)
- [Reference](https://www.chezmoi.io/reference/)

## Deployment
To use these dotfiles on a computer, run:

```bash
  chezmoi init git@github.com:DeamonCorpse/dotfiles.git
```
