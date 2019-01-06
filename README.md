# adwaita-extra-symbolic-icons
Extra symbolic icons for the Adwaita theme.

### Installation
Download:
```bash
git clone https://github.com/da-cali/adwaita-extra-symbolic-icons
```
Open directory
```bash
cd adwaita-extra-symbolic-icons/
```

Copy icons:
```bash
for i in ../adwaita-extra-symbolic-icons/icons/*.svg; do sudo cp $i /usr/share/icons/hicolor/symbolic/apps/; done
```

Update cache:
```bash
sudo gtk-update-icon-cache -f /usr/share/icons/hicolor/
```