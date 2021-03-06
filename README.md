# Adwaita Extra Symbolic Icons
A small collection of monochrome icons for a more cohesive look of the Gnome panel.

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
* To make certain icons work (like snaps) modify their .desktop file to the correct name (i.e: icon=spotify).
* If after the installation some icons become monochromatic, do:
  ```bash
  sudo cp icons/thunderbird.png /usr/share/icons/hicolor/128x128/apps/
  sudo cp icons/spotify.png /usr/share/icons/hicolor/256x256/apps/
  sudo cp icons/chromium.png /usr/share/icons/hicolor/256x256/apps/
  sudo cp icons/com.visualstudio.code.png /usr/share/icons/hicolor/256x256/apps/
  ```
  and update the cache again.