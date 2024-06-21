# Dotfile management

brew install stow

# Sync dir
stow -D . -S ~/dotfiles

# Sync file
stow -D . -S ~/dotfiles bashrc

# Updates
stow -D . -S ~/dotfiles

# Stow ignore file
.stowignore
