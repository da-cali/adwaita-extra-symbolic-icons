# adwaita-extra-symbolic-icons
A small collection of extra monochrome icons for the Gnome panel.

<img src="https://github.com/da-cali/adwaita-extra-symbolic-icons/blob/master/example.png" />

### Installation:

1. Download:
  ```bash
  git clone https://github.com/da-cali/adwaita-extra-symbolic-icons
  ```
2. Open directory:
  ```bash
  cd adwaita-extra-symbolic-icons/
  ```

3. Copy icons:
  ```bash
  for i in icons/*.svg; do sudo cp $i /usr/share/icons/hicolor/symbolic/apps/; done
  ```

4. Update cache:
  ```bash
  sudo gtk-update-icon-cache -f /usr/share/icons/hicolor/
  ```

### Notes:
* If after the installation your VS Code icon becomes monochromatic, do:
  ```bash
  sudo cp icons/code.png /usr/share/icons/hicolor/256x256/apps/
  ```
  and update the cache again.