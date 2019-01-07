# adwaita-extra-symbolic-icons
A small collection of extra monochrome icons for the Gnome panel.

<img src="https://github.com/da-cali/adwaita-extra-symbolic-icons/blob/master/example.png" />

### Installation
Download:
```bash
git clone https://github.com/da-cali/adwaita-extra-symbolic-icons
```
Open directory:
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