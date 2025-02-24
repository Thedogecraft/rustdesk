# rustdesk
installs yay and rustdesk on arch linux
```bash
sudo pacman -S --needed git base-devel && \
git clone https://aur.archlinux.org/yay.git && \
cd yay && makepkg -si --noconfirm && cd .. && rm -rf yay && \
yay -S --noconfirm rustdesk-bin

```
