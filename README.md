# 🚀 Arch Terminal Instant Customizer

Transform your vanilla Arch Linux terminal into a high-performance, aesthetic powerhouse in seconds. This script automates the installation of **Zsh**, **Oh My Zsh**, and the **Powerlevel10k** theme with essential productivity plugins.

## ✨ Features
- **Automated Install:** No manual editing of `.zshrc` required.
- **Unattended Setup:** Oh My Zsh is installed in "unattended" mode so the script finishes without interruption.
- **Enhanced Productivity:** Pre-configured with syntax highlighting and fish-style autosuggestions.
- **Arch Optimized:** Uses `pacman` for core dependencies.

## 📋 Prerequisites

### 1. Install a Nerd Font (Required for Icons)
Powerlevel10k uses special glyphs. For the best experience, install the Meslo Nerd Font:
```bash
sudo pacman -S ttf-meslo-nerd-font-powerlevel10k

# Clone the repository
git clone https://github.com/clencyc/archterminalwizard.git
cd archterminalwizard

# Make the script executable
chmod +x customizeterminal

# Run the script
./customizeterminal
