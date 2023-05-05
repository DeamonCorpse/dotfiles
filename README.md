# .dotfiles
Dotfiles saving and syncing between all my devices (ultimate goal) using [chezmoi](https://www.chezmoi.io/).

## Installation
- chezmoi can be installed with:
``` bash
sh -c "$(curl -fsLS get.chezmoi.io)" -- init --apply DeamonCorpse
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
- To use these dotfiles on a computer which already has chezmoi installed:
```bash
  chezmoi init git@github.com:DeamonCorpse/dotfiles.git
```

- To use on a computer where chezmoi *is not* installed:
- ``` bash
sh -c "$(curl -fsLS get.chezmoi.io)" -- init --apply git@github.com:DeamonCorpse/dotfiles.git
```
