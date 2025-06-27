# mpv-settings
My settings for mpv 0.40.0. This branch is more default-like and seemingly performs better on weaker hardware. Specs:
- Debian 13
- Intel i5-1335U
- Only iGPU supplied by the CPU above - Intel Iris Xe
- 16GB RAM
- NVMe SSD

### Usage (Linux)
```bash
# Installing:
mv ~/.config/mpv ~/mpv-old # backup old config to your home directory
git clone https://github.com/TaygaHoshi/mpv-settings.git ~/.config/mpv # clone this config to the correct location

# Updating:
cd ~/.config/mpv
git pull
```

### Sources
- [MPV documentation](https://mpv.io/manual/stable/)
- [Tsubajashi's config](https://github.com/tsubajashi/mpv-settings)
- [I am Scum's guide](https://iamscum.wordpress.com/guides/videoplayback-guide/mpv-conf)
