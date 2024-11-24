# dotfiles

This repository contains my personal dotfiles for managing and configuring my development environment across multiple machines.

## Included Configurations

- **Shell**: `.zshrc` for Zsh configuration
- **Prompt**: `starship.toml` for Starship prompt customization
- Other essential dotfiles for a smooth developer experience.

## How to Use

1. Install chezmoi:

   ```bash
   brew install chezmoi  # macOS
   sudo apt install chezmoi  # Ubuntu
   ```

2. Initialize the repository:

   ```bash
   chezmoi init https://github.com/landerox/dotfiles && chezmoi apply
   ```

## License

MIT
