# crux-sigil-27036
crux-sigil-27036 | [Arch@KDE]$> META; Player; Minimal; MMXXVI


Neofetch configuration bearing the seals.  
For the Arch build of 27.03.2026.

## Contains

- *Kyrie eleison, Christe eleison*
- 4B: *Basileus Basileon Basileuon Basileuononton*
- System info: Arch, KDE Plasma, eDEX-UI
- Hardware: i5-12400f, GTX 1080, 24GB
- Spotify integration (via `playerctl`)

## Installation

```bash
# Install dependency
sudo pacman -S playerctl

# Clone this repository
git clone https://github.com/ZEUX101/crux-sigil-27036.git
cd crux-sigil-27036

# Backup existing config
cp ~/.config/neofetch/config.conf ~/.config/neofetch/config.conf.bak

# Install
cp config.conf ~/.config/neofetch/

# Run
neofetch
```